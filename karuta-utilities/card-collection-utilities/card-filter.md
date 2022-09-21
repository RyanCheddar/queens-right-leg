---
description: Easily filter through your card collection with Card Filter
---

# Card Filter

Card Filters allow you to use Karuta-style filters to filter your card collection.

Currently, the following Card Collection Utilities support Card Filters:

* Collection Viewer
* Bulk Pricer
* Worker Viewer

## Supported Filters

{% hint style="info" %}
Some of these filters do not exist in Karuta and are only available in Leg!
{% endhint %}

* **Wishlist** _(w, wishlist, wishlists, wl)_\
  (e.g. `w<10`,`w>1000`)
* **Print Number** _(p, print, number)_\
  (e.g. `p<1000`,`p=1`)
* **Edition** _(e, ed, edition)_\
  (e.g. `e=3`, `e:2`)
* **Quality** _(q, quality)_\
  (e.g. `q:4`,`q<1`)
* **Character** _(c, character, name)_\
  (e.g. `c:luke`,`c=raiden_shogun`)
* **Series Name** _(s, series)_\
  (e.g. `s:tears_of_themis`,`s=genshin`)
* **Card Code** _(#, code)_\
  (e.g. `#:3bfxgn`, `#!vhvldt`)

The following filters may only be available in certain utilities:

* **Tag** _(t, tag)_\
  (e.g. `t!burn`,`t:cool`)\
  \[[Spreadsheet Utility](spreadsheet-utility.md) only]
* **Frame Status** _(framed, frame, f)_\
  (e.g. `f:t`, `framed=false`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/uAvlG5KcG3JdsaiwvkPu/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Applied Frame Name** _(framed, frame, f)_\
  __(e.g. `f:cherry_blossom`, `frame=bubble`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/uAvlG5KcG3JdsaiwvkPu/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Dye Status** _(dyed, dye, d)_\
  __(e.g. `d:t`, `dyed=false`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/uAvlG5KcG3JdsaiwvkPu/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Applied Dye Name/Code** _(dyed, dye, d)_\
  __(e.g. `d:red`, `dye=$rlxzf`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/uAvlG5KcG3JdsaiwvkPu/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Morph Status** _(morphed, morph, m)_\
  __(e.g. `m:t`, `morphed=false`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/uAvlG5KcG3JdsaiwvkPu/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Trim Status** _(trim, trimmed, tr)_\
  __(e.g. `tr:t`, `trimmed=false`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/uAvlG5KcG3JdsaiwvkPu/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Price** _($, price)_\
  (e.g. `$>3`,`$=0`)\
  \[[Collection Viewer](collection-viewer.md) & [Bulk Pricer](bulk-pricer.md) only]
* **Card Alias Status** _(a, alias, aliased)_\
  (e.g. `a:true`,`a=yes`)\
  \[Not available in Bulk Pricer outside Spreadsheet Utility Mode]
* **Card Injury Status** _(i, injured, injury)_\
  (e.g. `i:true`, `i=no`)\
  \[Not available in Bulk Pricer outside Spreadsheet Utility Mode]
* **Drop Server ID** _(server, guild)_\
  __(e.g. `server=[ID]`, guild!\[ID])\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]\
  (Note: This filter supports larger than (>) and smaller than (<) operations, if you somehow have a use for that.)
* **Grabber User ID** (_grabber_, _grabberid_)\
  (e.g. `grabber=[ID]`, `grabber![ID]`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]\
  (Note: This filter supports larger than (>) and smaller than (<) operations, if you somehow have a use for that.)
* **Dropper User ID** (_dropper_, _dropperid_)\
  (e.g. `dropper=[ID]`, `dropperid!none`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]\
  (Note: This filter supports larger than (>) and smaller than (<) operations, if you somehow have a use for that.)
* **Dropper Status** (_dropper)_\
  __(e.g. `dropper=true`, `dropper=false`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Grabber Status** (_grabber)_\
  __(e.g. `grabber=true`, `grabber=false`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]
* **Effort** _(ef_, _eff, effort)_\
  (e.g. `effort>300`, `eff<30`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility), or if effort data is available in Card Collection embed]
* **Max Possible Effort** (_maxEf_, _MaxEff_, _MaxEffort_)\
  (e.g. `maxEf<100`, `maxEffort:1`)\
  \[[Worker Viewer](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/lOuYypnvc11Yr03fUtS4/karuta-utilities/card-collection-utilities/worker-viewer) in [Spreadsheet Utility Mode](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only.]\
  (Note: Using this filter in the wrong utility or mode will lead to no cards being returned.)
* **Worker Mint Base Value** _(bv, basevalue)_\
  __(e.g. `bv>100`, `bv:0`)\
  \[[Worker Viewer](worker-viewer.md) only]
* **Worker Current Base Value** (c_bv_, _currentbasevalue_)\
  (e.g. c_bv>100_, c_bv:0_)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only]\
  (Note: Using this filter outside Spreadsheet Utility will lead to no cards being returned.)
* **Gender** (_gender_, _sex_)\
  (e.g. `gender=male`, `sex=nb`)\
  \[[Collection Viewer](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/DZJw8j2U729zLtHTjjqr/karuta-utilities/card-collection-utilities/collection-viewer) outside Spreadsheet Utility only]\
  (Genders supported are: male, female, non-binary, ambiguous, none, unknown)\
