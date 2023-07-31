//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[checkAndDisplayMessage](check-and-display-message.md)

# checkAndDisplayMessage

[androidJvm]\
open fun [checkAndDisplayMessage](check-and-display-message.md)(intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))

This method will check if there is a message to be displayed in the given intent and will display it. It has to be used in the onCreate and onNewIntent events if your activity does not extend [SMBaseActivity](../-s-m-base-activity/index.md). If you want to manage the display of the In-App Message linked to a push notification yourself, use the overload [checkAndDisplayMessage](check-and-display-message.md)

#### Parameters

androidJvm

| | |
|---|---|
| intent | the intent containing the message |
| context | the activity in which this method is called |

[androidJvm]\
open fun [checkAndDisplayMessage](check-and-display-message.md)(intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), inAppMessageDisplay: [SMInAppMessageDisplay](../-s-m-in-app-message-display/index.md))

This method will check if there is a message to be displayed in the given intent and will display it. It has to be used in the onCreate and onNewIntent events if your activity does not extend [SMBaseActivity](../-s-m-base-activity/index.md). This overload allows you to manage the display of the In-App Message linked to a push notification yourself

#### Parameters

androidJvm

| | |
|---|---|
| intent | the intent containing the message |
| context | the activity in which this method is called |
| inAppMessageDisplay | the [SMInAppMessageDisplay](../-s-m-in-app-message-display/index.md) interface instance that allows you to manage the display of an In-App Message |
