//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[retrieveNotificationMessage](retrieve-notification-message.md)

# retrieveNotificationMessage

[androidJvm]\
open fun [retrieveNotificationMessage](retrieve-notification-message.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessageRetrieved: [OnSMNotificationMessageRetrieved](../-on-s-m-notification-message-retrieved/index.md))

It will trigger the [onSuccess](../-on-s-m-notification-message-retrieved/on-success.md) when the [SMNotificationMessage](../-s-m-notification-message/index.md) is retrieved from the intent. If there is none in the intent, neither onSuccess nor onError will be triggered. If, for some reason, an error occurs, onError will be triggered.

#### Parameters

androidJvm

| | |
|---|---|
| intent | the Intent containing the push |
| notificationMessageRetrieved | the callback that will be triggered after retrieving the SMNotificationMessage |

#### See also

| |
|---|
| [OnSMNotificationMessageRetrieved](../-on-s-m-notification-message-retrieved/index.md) |
