---  
description: Change the Karuta prefix Leg listens to.  
---  

# Set Karuta Prefix

!!! info  
    Command: "leg karutaprefix \[Prefix]"  

This prefix is what Leg listens to in order to identify commands targeted at Karuta.  

This is mainly used for Cached Lookups and other features that intercept Karuta commands.  

!!! warning  
    Leg only listens to one prefix at a time. For example: If you set this to "k!", Leg won't respond when someone does "klu"  
