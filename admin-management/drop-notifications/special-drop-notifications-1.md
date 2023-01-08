# Special Print Drop Notifications

Special Print Drop Notifications allow you to ping a role when a drop contains a low/mid print card.

{% hint style="info" %}
Command: "leg printnotifications" / "leg printnotif"

Aliases: "printdropnotifications", "printdropnotif", "specialprintnotifications", "specialprintnotif"
{% endhint %}

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>Example of the printnotif command</p></figcaption></figure>

{% hint style="info" %}
When adding a role to be pinged using `leg printnotifadd [Role]`, you can also set a minimum print threshold for that role.\
\
For example, if a role is added with the threshold of #100 and a drop with a Print #9 card drops, the role will not be pinged.
{% endhint %}
