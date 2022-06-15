---
description: Locate a low/mid-print card with ease!
---

# Card Finder

Card Finder allows you to locate cards at or lower than 1000 print. Leg does this by scanning cards when they are displayed in a Karuta menu/interface.

{% hint style="info" %}
Command: "leg cardfinder [\[Character UUID\]](../../faq-frequently-asked-questions/whats-a-character-uuid.md) \<Edition (Optional)> \<p\[>/\</=]\[Print Number] (Optional)>"

Aliases: "printfinder", "cardfind", "trace", "cardtrace"



Using Print Number filtering also allows you to access card codes for cards with print numbers larger than 1000 (up to 20000).

\
Filtering by Print Number (and by extension, accessing cards with higher print than 1000) is a [Premium](../../boring-stuff/premium-access/)-only feature.
{% endhint %}

![Card Finder, finding Luke Pearce cards with print numbers less than 10.](<../../.gitbook/assets/image (3).png>)

{% hint style="warning" %}
Card Finder saves all cards, regardless of whether you disabled Leg commands.

If you don't feel comfortable with a card showing up in Leg, you can hide it using "leg hidecard \[Card Code].

Hidden cards stay hidden until they are unhidden by the card owner, or if they are transferred to another player.

Hiding a card in Leg does not mean it will be hidden in other bots with similar card tracing features, for obvious reasons.
{% endhint %}

{% hint style="info" %}
Card Finder currently listens to the following Karuta menus/interfaces:

* Card Details (kv/kci)
* Card Collection (kc)
* Card Multiburn (kmb)

In addition, Card Finder collects data from your entire Card Collection if you import your card collection into [Spreadsheet Utility](../card-collection-utilities/spreadsheet-utility.md).
{% endhint %}

### Privacy First

Card Finder is designed with privacy in mind.

Card Finder is designed to always only show cards for a character, instead of cards owned by a specific user.

Card Finder also launched with a card hiding functionality, for the few cards that you don't want people to bother you about, or the cards with special value to you.
