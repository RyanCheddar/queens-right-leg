---
description: How Leg processes your information.
---

# Privacy Policy

#### The following information are collected anonymously and are not linked to any users, Karuta cards or server:

* Karuta character data\
  (Name, Series, Wishlist, Aliases, Image URL, Drop statistics etc.)
* Karuta frames\
  (Name, Image URL, Price)
* Drop Analytics\
  (To power features such as "leg droptrend")\
  (Can be opted-out of by disabling Drop Analysis in "leg featureset")
* Anonymous error logs\
  (Only contains information about which part of Leg is malfunctioning)

#### The following information may be linked to users/cards/servers but are not publicly viewable:

* User bits\
  (Collected automatically, can be deleted by disabling _Automatic Bit Caching_ in "leg userconfig")
* Aliases found from any Karuta Koibito Dating Menus\
  (Linked to the card you use to visit)\
  (Collected automatically, data deleted once you open the visiting card's Card Info menu with "kci")\
  (Disabled when you turn off _Enable Leg Commands_ in "leg userconfig")
* Your last obtained card from Karuta\
  (Used by Leg to provide you automatic cached lookup when Karuta is on cooldown)\
  (Can be disabled by turning off _Enable Leg Commands_ in "leg userconfig")
* Your Leg Reminders\
  (Deletable by manually removing all entries using "leg reminders")
* Personal Wishlist\
  (Deletable by manually removing all entries using "leg wishlist")
* Premium access \[Personal]\
  (Your Premium access information is only viewable by you.)
* Feature Configurations\
  (For obvious reasons, this has to be linked to you.)
* Spreadsheet Utility Data\
  (Not accessible by anyone else, automatically deleted 3 days after importing.)

#### The following information is linked to users/cards/servers and is publicly viewable:

* User dyes\
  (Collected only when you authorize Leg to. You can unauthorize and delete this data with "leg dyeunauth")
* Premium access \[Servers]\
  (The duration of a server's Premium access may be viewable to all server members.)\
  (Personal Premium access information is not viewable by anyone other than you.)
* Cards cached by Card Finder\
  (If you are the owner of the card, you can hide it using "leg hidecard \[Card code]")

### Purchasing Premium access with Tebex (IRL Money)

By purchasing Premium access with Tebex, @RyanC#5785 will receive your Discord username (and ID), and possibly your email as well.

{% hint style="info" %}
Payments are handled via Tebex. You can check out their Privacy Policy [here](https://www.tebex.io/legal/privacy)
{% endhint %}

Information regarding your purchase may be retained (Logs about who you are, when the purchase took place, what server you redeemed to etc.) in case of chargebacks, refunds and etc.

### Data Deletion

#### Users

If you want to completely wipe all your user data off Leg, you can do "leg forgetme".

ForgetMe will:

* Remove all user data associated to you in Leg's database
* Resets your User Configurations to default

However, ForgetMe does not:

* Delete your data contributions\
  (Things such as the cards you lookup, characters you've looked up, Karuta information you've pulled up and etc.)\
  (This is because these data are not linked to you.)
* Delete Premium access information about you\
  (This information auto-deletes once your Premium access expires and you have no remaining tokens)
* Delete information about low/mid print cards owned by you\
  (You will need to use "leg hidecard \[Card Code]")

#### Servers

For servers, removing data from Leg is as simple as kicking Leg from your server.

The following information might be retained:

* Premium access information if your server has leftover duration or tokens
* Personal Wishlist data from members
* Feature Configurations

{% hint style="info" %}
Logs about your usage of Leg commands may be stored for debugging purposes.

These logs contain the time you ran a command, your username and ID, the command you ran, any parameters in the command and etc.

If your server uses a common syntax (e.g. "l"), non-command messages might also be included in the logs.

These logs are wiped during bot restarts, and are not accessed unless necessary.
{% endhint %}
