---
description: Import your entire Card Collection into Leg, all at once.
---

# Spreadsheet Utility

With Spreadsheet Utility, you are able to use Collection Utilities such as Collection Viewer and others without needing to run Karuta's Card Collection command first!

Not only that, when using Spreadsheet Utility, you can have your ENTIRE Card Collection in any Leg utility at once!

{% hint style="info" %}
Spreadsheet Utility can be run by doing "ksheet" or equivalent in Karuta. Importing takes a while, but you can immediately start using Card Collection Utilities that work with Spreadsheet Utility.\


If you want Spreadsheet Utility to stop appearing when you do "ksheet", you can disable it with ["leg userconfig spreadsheet\_utility false"](../../bot-management/user-feature-configuration/list-of-user-configurable-features/spreadsheet\_utility.md)
{% endhint %}

{% hint style="warning" %}
Usage of Spreadsheet Utility will also import all of your cards into Card Finder. This is an invisible process, and the only way to not have this happen is to not use Spreadsheet Utility.
{% endhint %}

{% hint style="success" %}
For privacy and data accuracy reasons, Spreadsheet Utility data is automatically deleted 3 days after importing. This does not remove your cards from Card Finder, however.
{% endhint %}

### I imported my Card Collection. What now?

After importing, you can run the following Card Collection utilities without needing to reply to your Card Collection!

* [Collection Viewer](collection-viewer.md) (Browse through your entire Card Collection) \[leg cv]
* [Bulk Pricer](bulk-pricer.md) (Price cards from your Card Collection, with cosmetics accounted for!) \[leg bp]
* [Worker Viewer](worker-viewer.md) (View highest Base Value cards in your Card Collection, as well as injury times) \[leg wv]

### Functionality Differences with Spreadsheet Utility

Some functionality work differently when you're using a Card Collection Utility in Spreadsheet Utility Mode.

* Current Base Value is shown in addition to Mint Base Value \[Worker Viewer]
* Estimated Pricing accounts for cosmetics and other aspects of a card as well \[Collection Viewer, Bulk Pricer]
* Cards' tags are visible and filterable \[All Utilities]
* Accurate injury timers are available for injured cards \[Worker Viewer]
* Tile View is not available \[Collection Viewer]
* Sorting is enabled by default and cannot be disabled \[Bulk Pricer]
