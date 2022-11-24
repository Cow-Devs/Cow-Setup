---
description: >-
  The muted role can only be set by members with both Manage Server and Manage
  Roles permissions.
---

# 🤐 Mutes

Mutes are the slightest bit complicated. They use a role that you can set or have the bot automatically create with the proper permissions. These are the two options:

#### 1. Set a muted role

This is a simple process of you using /moderation setmutedrole then selecting a role. The role id will be stored within the bot's files and is used when attempting to mute a member. This stored role will also be used for unmutes.

![](<.gitbook/assets/image (11).png>)

#### 2. Let the bot make one

If you attempt to mute a member without a muted role set, the bot will make one for you. It will also set your muted role as this role. This will not happen with unmutes.

![](<.gitbook/assets/image (5).png>)![](<.gitbook/assets/image (18).png>)

The bot will log any mutes and unmutes to your modlog channel if you one set.
