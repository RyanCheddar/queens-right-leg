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
* **Effort** _(eff, effort)_\
  (e.g. `effort>300`, `eff<30`)\
  \[[Spreadsheet Utility](https://app.gitbook.com/s/0OfyDder0TDbYepM9qYh/\~/changes/OlSca5zoO5YwB4EQOnye/karuta-utilities/card-collection-utilities/spreadsheet-utility), or if effort data is available in Card Collection embed]
