---
description: >-
  Personal Wishlist allows you to get pinged when a character you want drops, no
  matter what channel they're in.
---

# Personal Wishlist

Personal Wishlist works like Karuta's Wishlist system, with the difference being that Personal Wishlist works across an entire server.

{% hint style="warning" %}
Personal Wishlist is per-server. Adding a character to your Personal Wishlist in one server doesn't mean you'll be notified for them in other servers.
{% endhint %}

{% hint style="warning" %}
Personal Wishlist only works when a server has both Personal Wishlist and Drop Analysis enabled. Leg will tell you if Personal Wishlist is disabled, but won't warn you if Drop Analysis is unavailable.
{% endhint %}

To view your Personal Wishlist characters, do "leg wishlist".

To add a character to your Personal Wishlist, do "leg wishlistadd \[Character UUID]"

To remove a character, do "leg wishlistremove \[Character UUID]"

{% hint style="info" %}
Don't know what a Character UUID is? Head here: [What's a Character UUID?](../../faq-frequently-asked-questions/whats-a-character-uuid.md)
{% endhint %}

{% hint style="info" %}
You can be notified when a character on any of your Personal Wishlists appears on the [Leg Marketplace](../../karuta-services/leg-marketplace.md) by enabling marketplace\_notif in your [User Feature Configuration (leg userconfig)](../../bot-management/user-feature-configuration/)
{% endhint %}

{% hint style="success" %}
Server Owners: If you want to delete the personal wishlist of users who are no longer in your server, run `leg wishlistclearadmin` to clear these users' wishlists, so you'll stop getting broken pings for no reason!
{% endhint %}
