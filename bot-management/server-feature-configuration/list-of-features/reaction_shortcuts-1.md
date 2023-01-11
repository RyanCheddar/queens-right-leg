---
description: Allow self-added reaction shortcuts
---

# self\_reaction

This controls whether Leg will respond to reactions on Karuta embeds, even if Leg didn't add the reaction himself (either because [reaction\_shortcuts](reaction\_shortcuts.md) is off, because you/your server doesn't have Premium, or because someone already used reaction shortcuts on the message before)

{% hint style="danger" %}
Enabling this feature can cause disasters if your server has third-party bots with reaction capabilities (e.g. Keqing).\
\
Additionally, you should consider using [channeloverride](../channel-feature-override.md) this feature to off if you have announcement channels where users can add reactions.
{% endhint %}

![The moneybag emoji is an example of a Reaction Shortcut for "leg price"](<../../../.gitbook/assets/image (13).png>)
