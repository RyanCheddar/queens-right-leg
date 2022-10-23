---
description: Give Leg access to your dye data
---

# Update Dye Data

{% hint style="info" %}
Command: "leg dyeupdate"\
Aliases: "updatedyes", "updatedye"

You may need to do "kdyes" first before running this command.
{% endhint %}

In order to use dye-related commands, you must first give Leg access to your dye data.

If you have never done this command before, you will be asked whether you want to authorize Leg to access your dye data. Once you do this, your dyes may become publicly viewable to anyone.

To unauthorize Leg and delete your dye data, do "leg dyeunauth".

{% hint style="warning" %}
This feature is not provided or supported by Karuta. Leg simply visits your dye page and looks through the dyes you own, **only** if you allow it to. \


For privacy reasons (and to respect Karuta privacy settings), Leg **will never** obtain your dye data without your consent. Even if you have provided authorization, you still need to run dyeupdate manually to keep Leg's dye database up-to-date.
{% endhint %}

{% hint style="success" %}
You will be able to make your dyes private in a future update.
{% endhint %}
