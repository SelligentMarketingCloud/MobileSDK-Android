//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[setNotificationMessageAsReceived](set-notification-message-as-received.md)

# setNotificationMessageAsReceived

[androidJvm]\
open fun [setNotificationMessageAsReceived](set-notification-message-as-received.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessage: [SMNotificationMessage](../-s-m-notification-message/index.md))

It sends a PushReceived event to the Selligent Mobile Platform. Make sure this is only called once per push as it will send the event everytime.

#### Parameters

androidJvm

| | |
|---|---|
| notificationMessage | the SMNotificationMessage to mark as received |

#### See also

| |
|---|
| [SMNotificationMessage](../-s-m-notification-message/index.md) |
