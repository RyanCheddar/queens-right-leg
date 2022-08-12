# Wishlist Count Notifications

Wishlist Count Notifications allow you to make a role get pinged when a drop contains a character over x wishlist.

{% hint style="info" %}
Command: "leg wishlistnotifications" / "leg wishlistnotif"\
\
Wishlist Count Notifications is a [Premium](../../boring-stuff/premium-access/server-premium.md)-only feature.
{% endhint %}

![Example of the wishlistnotif command](<../../.gitbook/assets/image (35).png>)

{% hint style="info" %}
You can also set an upper limit on wishlist count. This allows you to give users more granular control over what they're pinged for, or even lock higher wishlist pings behind level roles or server supporter roles.\
\
To do so, just run "leg wishlistnotifadd \[Role ID] \[Threshold]-\[Upper Limit]"\
\
As an example, locking a role to only ping when a drop has a wishlist count between 20 and 200 can be done with "leg wishlistnotifadd \[Role] 20-200".
{% endhint %}
