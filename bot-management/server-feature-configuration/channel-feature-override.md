---
description: Enable/Disable features for a specific channel only
---

# Channel Feature Override

{% hint style="info" %}
Command: "leg channeloverride"

Aliases: "channelconfig", "channelfeatureset"
{% endhint %}

With Channel Feature Override, you can change a feature's setting for only one channel.

Once you do the command, you'll be greeted with an interface similar to "leg featureset".

<img src="../../.gitbook/assets/image (28).png" alt="" data-size="line"> If you see \[Inherited] next to a feature, this feature is being controlled by the [Global Configuration (a.k.a. "leg featureset")](./). If you change this setting for the guild, this channel will also be updated with the new setting.

<img src="../../.gitbook/assets/image (25).png" alt="" data-size="line"> If you don't see \[Inherited], this feature was specifically changed for this channel. It will not be affected by the Global Configuration no matter what changes you make.

Changing a feature's configuration using "leg channeloverride \[type] true/false" will result in it no longer inheriting. To make it reinherit the Global Configuration, do "leg channeloverride \[true] inherit", or press "Reset Channel Config" which resets all settings to use inheritance.
