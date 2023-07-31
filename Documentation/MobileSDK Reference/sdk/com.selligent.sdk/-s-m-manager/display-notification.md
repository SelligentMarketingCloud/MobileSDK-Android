//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[displayNotification](display-notification.md)

# displayNotification

[androidJvm]\
open fun [displayNotification](display-notification.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html))

This method is to be used only if you set [DoNotListenToThePush](../-s-m-settings/-do-not-listen-to-the-push.md) to true. It will create a notification based on the information present in the intent and will display it. If the app is in foreground and the setting [RemoteMessageDisplayType](../-s-m-settings/-remote-message-display-type.md) is set to 'Automatic', the SDK will display the in-app message linked to the push right away without going through a notification.

#### Parameters

androidJvm

| |
|---|
| context |
| intent | it contains all the push information. If you retrieve the push using the FirebaseMessagingService method onMessageReceived, simply call toIntent() on the RemoteMessage object received. |
