//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMInAppMessageDisplay](index.md)/[onBeforeDisplay](on-before-display.md)

# onBeforeDisplay

[androidJvm]\
abstract fun [onBeforeDisplay](on-before-display.md)(message: [SMInAppMessage](../-s-m-in-app-message/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

This method is called before displaying an In-App Message linked to a push notification.

#### Return

true if you want the SDK to display the In-App Message, return false if you want to do it yourself.

## Parameters

androidJvm

| | |
|---|---|
| message | the [SMInAppMessage](../-s-m-in-app-message/index.md) |
