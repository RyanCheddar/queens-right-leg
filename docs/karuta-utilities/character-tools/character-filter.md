---
description: Special filters for characters
---

# Character Filter

Character Filters allow you to use Karuta-style filters to filter characters.

Character Filters can currently only be used with Cached Lookup. It uses similar filters to Card Filters.

Character Filters work best when Cache Lookup is run with no input (i.e. `leg lu`). 

## Operators
* Equality and Inequality (`=` equal, `:` is, `!` is not, `!=` not equal)
* Integer Comparison (`<` less than, `>` greater than, `<=` less than or equal, `>=` greater than or equal)
* Integer roughly equal (`~=` roughly equal, `~` roughly)
  (The number of tildas (~) you use represents how loose the comparison should be.)
  ("\~" ±5, "\~\~" ±10, "\~\~\~" ±20, "\~\~\~" ±30, etc.)

## Supported Filters

* **Character** _(c, character, name)_\
  (e.g. `c:luke`,`c=raiden_shogun`)
* **Series Name** _(s, series)_\
  (e.g. `s:tears_of_themis`,`s=genshin`)
* **Wishlist** _(w, wishlist, wishlists, wl)_\
  (e.g. `w<10`,`w>1000`)
* **Total Edition Count** _(e, ed, eds, edition, editions)_\
  (e.g. `e=8`, `e:1`)
* **Gender** (_gender_, _sex_)\
  (e.g. `gender=male`, `sex=nb`)\
* **Koibito** _(koi, koibito)_\
  (e.g. `koi:396545298069061642`)
* **Koibito Since** _(koi_since, koibito_since, koibitosince)_\
  (e.g. `koi_since<1790642423`, `koi_since!=0`)
  (Note: This uses [Unix Epochs](https://www.epochconverter.com/), or number of seconds since Jan 1 1970 UTC.)
  (Characters with no Koibito will use a timestamp of 0. You may need to add an extra filter to exclude 0s.)

* **Dojo Stats** _(body, mind, soul, courage, faith, morality, harmony, insight)_
  (e.g. `body~=10`, `mind<50`)
