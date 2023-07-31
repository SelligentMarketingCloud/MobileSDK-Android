//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[executeButtonAction](execute-button-action.md)

# executeButtonAction

[androidJvm]\
open fun [executeButtonAction](execute-button-action.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), button: [SMNotificationButton](../-s-m-notification-button/index.md), message: [SMInAppMessage](../-s-m-in-app-message/index.md))

This method will execute the action attached to the given [SMNotificationButton](../-s-m-notification-button/index.md) of the given [SMInAppMessage](../-s-m-in-app-message/index.md). It will also send an event to the platform to inform the button was clicked. Use this method if you do not want to implement our Fragments.

#### Parameters

androidJvm

| | |
|---|---|
| context | the current [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html). |
| button | the [SMNotificationButton](../-s-m-notification-button/index.md) containing the action to execute. |
| message | the corresponding [SMInAppMessage](../-s-m-in-app-message/index.md). |
