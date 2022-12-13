---
description: Copies a message from the current channel to another channel.
---

# Copy

<figure><img src="../../.gitbook/assets/Seymour-Copy.gif" alt=""><figcaption></figcaption></figure>

## Command

/copy `message-id` `new-channel`

## Action

Copies the message with the given id including all attachments to the specified channel.

## Response

{% hint style="success" %}
Copied to \<Channel>
{% endhint %}

{% hint style="danger" %}
* Not a valid message id provided.
* Channel \<Channel> can't be accessed.
* Missing write permission in the target channel.
* Message not found.
{% endhint %}
