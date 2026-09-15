---
description: How Leg processes your information.
---

# Privacy Policy

{% hint style="info" %}
Any enquiries can be sent to our Support Server, our twitter (@LegTheBot) or our email at leg@ryansbakery.dev
{% endhint %}

Leg takes great care in handling your privacy transparently, as you deserve to know about how your information is being processed.

Here are quick rundowns of what information Leg processes and stores, and other things that you might want to know.

#### The following information are processed anonymously and are not linked to any users, Karuta cards or server:

* Karuta character data\
  (Name, Series, Wishlist, Aliases, Image URL, Drop statistics etc.)
* Karuta frames\
  (Name, Image URL, Price)
* Drop Analytics (No. of drops globally, no. of wishlist cards dropped etc.)\
  (Can be opted-out of by disabling Drop Analysis in "leg featureset")
* Anonymous error logs\
  (Only contains information about which part of Leg is malfunctioning)

#### The following information may be linked to users/cards/servers but are not publicly viewable:

* User bits\
  (Collected automatically, can be deleted by disabling _Automatic Bit Caching_ in "leg userconfig")
* Aliases found from any Karuta Koibito Dating Menus\
  (Linked to the card you use to visit)\
  (Collected automatically, data deleted once you open the visiting card's Card Info menu with "kci")\
  (Disabled when you turn off _Enable Leg Commands_ in "leg userconfig". This will render Leg unusable for you.)
* Your last obtained card from Karuta\
  (Used by Leg to provide you automatic cached lookup when Karuta is on cooldown)\
  (Can be disabled by turning off _Enable Leg Commands_ in "leg userconfig". This will render Leg unusable for you.)
* Your Leg Reminders\
  (Deletable by manually removing all entries using "leg reminders")
* Personal Wishlist\
  (Deletable by manually removing all entries using "leg wishlist")
* Premium access \[Personal]\
  (Your Premium access information is only viewable by you.)
* Feature Configurations\
  (For obvious reasons, this has to be linked to you/your server.)
* Spreadsheet Utility Data\
  (Not accessible by anyone else, automatically deleted 3 days after importing.)

#### The following information is linked to users/cards/servers and is publicly viewable:

* User dyes\
  (Collected only when you authorize Leg to. You can unauthorize and delete this data with "leg dyeunauth", and you can make it private with "leg userconfig dye\_public false")
* Premium access \[Servers]\
  (The duration of a server's Premium access may be viewable to all server members.)\
  (Personal Premium access information is not viewable by anyone other than you.)

### Purchasing Premium access with Tebex (IRL Money)

By purchasing Premium access with Tebex, the developers of Leg will receive the following sensitive information:

* Payment Method used
* Amount of money transacted
* Premium packages you have purchased
* Your full name
* Your Discord username
* Your email address (not shared if you do not tick the checkbox during checkout)
* Your IP address at the time of purchase

{% hint style="warning" %}
All information listed above cannot be deleted, because Tebex does not offer the tools to do so.
{% endhint %}

{% hint style="info" %}
Payments are handled via Tebex. You can check out their Privacy Policy [here](https://www.tebex.io/legal/privacy)
{% endhint %}

Other information regarding your purchase (that are not provided by Tebex) may be retained (Logs about who you are, when the purchase took place, what server you redeemed to etc.) in case of chargebacks, refunds and etc. This information can be requested for deletion after 180 days.

### Data Deletion

#### Users

If you want to completely wipe all your user data off Leg, you can do "leg forgetme".

ForgetMe will:

* Remove all user data associated to you in Leg's database
* Resets your User Configurations to default

However, ForgetMe does not:

* Delete Premium access information about you\
  (This information auto-deletes once your Premium access expires and you have no remaining tokens)

#### Servers

For servers, removing data from Leg is as simple as kicking Leg from your server.

The following information might be retained:

* Premium access information if your server has leftover duration or tokens
* Personal Wishlist data from members
* Feature Configurations

After a period of not using Leg in your server (max. 180 days), all information associated to your server will be removed.

You can also request immediate data removal by contacting @RyanC#5785 on Discord.

{% hint style="info" %}
Logs about your usage of Leg commands may be stored for debugging purposes.

These logs contain the time you ran a command, your username and ID, the command you ran, any parameters in the command and etc.

Messages containing Leg's syntax but do not correspond to actual commands may also be stored. If your server uses a common syntax (e.g. "l"), this might happen more frequently.

These logs are wiped during bot restarts, and are not accessed unless necessary. These logs cannot be accessed by anyone other than the developers.
{% endhint %}
