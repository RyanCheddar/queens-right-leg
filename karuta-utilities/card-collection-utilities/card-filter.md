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
  (Note: This filter also supports larger than (>) and smaller than (<) operations, unlike Karuta)
* **Effort** _(ef_, _eff, effort)_\
  (e.g. `effort>300`, `eff<30`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility), or if effort data is available in Card Collection embed]
* **Max Possible Effort** (_maxEf_, _MaxEff_, _MaxEffort_)\
  (e.g. `maxEf<100`, `maxEffort:1`)\
  \[[Worker Viewer](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/lOuYypnvc11Yr03fUtS4/karuta-utilities/card-collection-utilities/worker-viewer) in [Spreadsheet Utility Mode](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only. Requires you to select _"Sorting by Max Possible Effort"_ at least once first.]\
  (Note: If you didn't follow the above steps or is using the wrong utility, this filter will cause no cards to be returned.)
* **Worker Base Value** _(bv, basevalue)_\
  __(e.g. `bv>100`, `bv:0`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) or [Worker Viewer](worker-viewer.md)]\
  (Note: This filters by _current_ base value in Spreadsheet Utility, and _mint_ base value in Worker Viewer _when outside Spreadsheet Utility_.)
* **Worker Mint Base Value** (_mbv_, _mintbasevalue_)\
  (e.g. _mbv>100_, _mbv:0_)\
  \[[Worker Viewer](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/lOuYypnvc11Yr03fUtS4/karuta-utilities/card-collection-utilities/worker-viewer) in [Spreadsheet Utility Mode](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility) only. Requires you to select _"Sorting by Mint Base Value"_ or _"Sorting by Max Possible Effort"_ at least once first.]\
  (Note: If you didn't follow the above steps or is using the wrong utility, this filter will cause no cards to be returned.)\
