---
title: "attachMenuBot"
description: "Represents a bot web app that can be launched from the attachment menu »"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: attachMenuBot  
[Back to constructors index](/API_docs/constructors/index.html)



Represents a [bot web app that can be launched from the attachment menu »](https://core.telegram.org/api/bots/attach)

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|inactive|[Bool](/API_docs/types/Bool.html) | Optional|Whether this bot attachment menu entry should be shown in the attachment menu (toggle using [messages.toggleBotInAttachMenu](../methods/messages.toggleBotInAttachMenu.html))|
|has\_settings|[Bool](/API_docs/types/Bool.html) | Optional|True, if the bot supports the ["settings\_button\_pressed" event »](https://core.telegram.org/api/bots/webapps#settings-button-pressed)|
|bot\_id|[long](/API_docs/types/long.html) | Yes|Bot ID|
|short\_name|[string](/API_docs/types/string.html) | Yes|Attachment menu item name|
|peer\_types|Array of [AttachMenuPeerType](/API_docs/types/AttachMenuPeerType.html) | Yes|List of peer types where this attachment should be shown|
|icons|Array of [AttachMenuBotIcon](/API_docs/types/AttachMenuBotIcon.html) | Yes|Attachment menu icon|



### Type: [AttachMenuBot](/API_docs/types/AttachMenuBot.html)


### Example:

```
$attachMenuBot = ['_' => 'attachMenuBot', 'inactive' => Bool, 'has_settings' => Bool, 'bot_id' => long, 'short_name' => 'string', 'peer_types' => [AttachMenuPeerType, AttachMenuPeerType], 'icons' => [AttachMenuBotIcon, AttachMenuBotIcon]];
```  
