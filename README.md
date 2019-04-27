This Rimworld mod adds the ability to Auto Sell items from the trade window using a set of editable rules.  These rules can be created and edited via the Autosell Tab.

So, You've been hoarding a ton of weapons and apparel you've been hoping to sell, or you're frequently harvesting and selling something, but you're getting sick of adjusting sliders for all your hundreds of items.  This is mod will make your life easier. After you setup your rules for selling on the overview tab, selling will be only one button press away.

You can create rules for damage equipment, sell only of a certain quality, or even items made from a certain material.  Do you have a surplus of stock but don't want to sell everything, you can do that as well.

**Additional Info**

If you plan to use AutoSeller with caravans, you'll need to build a Trade Reports Printer and create a shopping list, and be sure to take the Shopping List with you. A Shopping List will connect your caravan with the original colony the list was created on (as long as that colony still has a trade printer) use when sending your caravan to trade with other faction bases.

If AI Selling is enabled it will, by default give a job to the best negotiator available, some social skill is also gained during the job.

Buying Rules can be set buy creating a rule as normal, and setting the Reorder Point and Restock Levels. when your stock goes below the Reorder Point, you will buy stock up to the Restock Level. By setting Sell Point and Reorder Points, you can avoid getting too low levels of stock or storing too much of an item.

**Specific AutoSeller 2 features**

Users of the old AutoSeller might scream AHHH! at the new rule creating interface, however the new modular design allows for more complex rule creation while still allowing you to create a rule in under 20 seconds if you want (yes I've tried it).

Another advantage of the new modular design is that there aren't different Rule Types for trading different things (gone are the days of Items/Livestock/Building rules).

You get to choose which filters to add, if you want to sell all of something regardless of health, you don't have to use the health filter.

AutoSeller is an Extendible Framework, and can use Filters outside of the main mod, as well as extensions to create rules that can be used outside of Trading.


**Creating a rule in AutoSeller 2**


Rules now consist of Groups and Filters.  Rule options/settings are at the top of the interface, be sure to set the Rule Description, since unlike AutoSeller 1, Rules are not named for you (this is because rules can become very complex)

Groups don't do anything by themselves but they can hold Filters and other Groups.  You can completely ignore using Groups if you want and only use the Root Group to store your Filters.

The right side of the screen contains Properties Tabs for viewing the properties of Groups or Filters

With a Group selected, and from the Group Properties tab on the right side of the interface, double click on Add Filter, this will bring up available filters, click on your chosen filter to add it.  Each Filter has different Properties you can manipulate, once added you can double click on it to access these properties.

Click accept to save your rule.


**Tips**

You can test your rule to see what items match it on the Test tab during rule creation, please note that this matches against what is in your colony (note that quantity is deliberately not shown since this can vary greatly when trading) so if your colony doesn't have an item matching, it wont show.

The most used filter is the Category Filter and I suggest using this filter for your first rule.  For the Category Filter, browse through the categories and select which item types or categories to add from the list right of the category list (you can hold shift or/and ctrl to manipulate this list). Added items/categories will be shown on the list below, to remove items from this list, browse back to it to it from categories and deselect.

You can change how a group processes filters by toggling whether a group uses an OR or an AND operator using right click.  These are displayed on the group as a Venn diagram, which is two overlapping circles, OR has both circles filled where AND has only the intersection between circles filled. The default group behaviour is AND.  

When creating complex rules with multiple branches of Groups, it is highly recommended to name your group (top right of the interface)

You can invert the results of a group by right clicking and selecting Negate, this can be used for creating exceptions which I will get into later as it is an advanced topic.

If you want do prevent a rule from firing but not delete it, you can click the S next to the Rule on the AutoSeller Overview.  while on the topic of deactivating rules, you can deactivate part of a rule by editing the rule and right clicking the Group you wish to deactivate.

There are multiple ways to Manipulate Groups, you can cut and paste a Group onto another Group, or you can simply drag the Group over to where you want.

Did you know that you can copy/paste a group from one rule to different rule, you can even do this with different extension Rules.
