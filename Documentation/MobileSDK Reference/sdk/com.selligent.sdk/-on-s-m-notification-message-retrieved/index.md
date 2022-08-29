//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[OnSMNotificationMessageRetrieved](index.md)

# OnSMNotificationMessageRetrieved

[androidJvm]\
interface [OnSMNotificationMessageRetrieved](index.md)

This allows to write codes that will be executed after an event is sent to the Selligent platform

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMNotificationMessage](../-s-m-notification-message/index.md) |  |
| [com.selligent.sdk.SMManager](../-s-m-manager/retrieve-notification-message.md) |  |

## Functions

| Name | Summary |
|---|---|
| [onError](on-error.md) | [androidJvm]<br>abstract fun [onError](on-error.md)(exception: [Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html))<br>Event triggered when an error occurred while retrieving the SMNotificationMessage |
| [onSuccess](on-success.md) | [androidJvm]<br>abstract fun [onSuccess](on-success.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessage: [SMNotificationMessage](../-s-m-notification-message/index.md))<br>Event triggered when the SMNotificationMessage is retrieved. |
