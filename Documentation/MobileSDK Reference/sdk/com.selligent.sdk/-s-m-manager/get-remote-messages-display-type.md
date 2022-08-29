//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[getRemoteMessagesDisplayType](get-remote-messages-display-type.md)

# getRemoteMessagesDisplayType

[androidJvm]\
open fun [getRemoteMessagesDisplayType](get-remote-messages-display-type.md)(): [SMRemoteMessageDisplayType](../-s-m-remote-message-display-type/index.md)

Gets the way remote messages are displayed when the app is in foreground. If Automatic, no notification will be created, the message will be displayed right away. If Notification, a notification will be created and the message will be displayed only after clicking on it. If None, nothing will happen, the app will need to manage the display of the message (cf. [getLastRemotePushNotification](get-last-remote-push-notification.md), [displayLastReceivedRemotePushNotification](display-last-received-remote-push-notification.md) )

#### Return

the [SMRemoteMessageDisplayType](../-s-m-remote-message-display-type/index.md)
