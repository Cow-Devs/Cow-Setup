---
description: Setting the modmail channel requires Manage Server and Manage Webhooks.
---

# 📧 Modmail

Cow Modmail is a way of having members speak to staff anonymously using randomly generated tokens/IDs. Staff my respond to the messages using the IDs, while never revealing the original sender.

## How to set a modmail channel

### Step 1: Create a webhook

In the channel you wish to have modmail messages sent to, open settings and create a webhook.

![](<.gitbook/assets/image (23).png>)![](<.gitbook/assets/image (24).png>)

### Step 2: Set the channel

Copy the webhook url. **Never share a webhook url**. From there you can set the channel with /modmail setchannel. You should receive a message in that channel.

![](<.gitbook/assets/image (10).png>)![](<.gitbook/assets/image (6).png>)![](<.gitbook/assets/image (22).png>)

## Sending and replying to messages

### Sending

Sending is very simple. Just use /modmail send and you will already be done.

![](<.gitbook/assets/image (3).png>)

### Replying

Replying is still simple. You should see something like this.

![](<.gitbook/assets/image (7).png>)

See that ID? Just use /modmail reply, having token\_id being that id. Your response has been DMed to the user.

![](<.gitbook/assets/image (19).png>)![](<.gitbook/assets/image (12).png>)
