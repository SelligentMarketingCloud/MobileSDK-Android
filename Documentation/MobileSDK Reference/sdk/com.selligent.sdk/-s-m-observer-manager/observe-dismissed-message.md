//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMObserverManager](index.md)/[observeDismissedMessage](observe-dismissed-message.md)

# observeDismissedMessage

[androidJvm]\

@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)

open fun [observeDismissedMessage](observe-dismissed-message.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)observer: [Observer](https://developer.android.com/reference/kotlin/androidx/lifecycle/Observer.html)&lt;[Void](https://developer.android.com/reference/kotlin/java/lang/Void.html)&gt;)

Use this method to get notified when an In-App message is about to be dismissed. It replaces the broadcast BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION. It must be called on the main thread. Observing using this method will trigger the onChanged event of the observer only when the value changes after the observer is created. If there is already a value at that moment, the event will not get triggered. To change that behaviour, use the overload [observeDismissedMessage](observe-dismissed-message.md)

## Parameters

androidJvm

| | |
|---|---|
| lifecycleOwner | The LifecycleOwner that will be used to automatically start and stop listening. Most of the time, it will be the Activity you are in. |
| observer | The Observer that will listen to the event and get triggered when it happens |

[androidJvm]\

@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)

open fun [observeDismissedMessage](observe-dismissed-message.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)observer: [Observer](https://developer.android.com/reference/kotlin/androidx/lifecycle/Observer.html)&lt;[Void](https://developer.android.com/reference/kotlin/java/lang/Void.html)&gt;, triggerEveryTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Use this method to get notified when an In-App message is about to be dismissed. It replaces the broadcast BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION. It must be called on the main thread.

## Parameters

androidJvm

| | |
|---|---|
| lifecycleOwner | The LifecycleOwner that will be used to automatically start and stop listening. Most of the time, it will be the Activity you are in. |
| observer | The Observer that will listen to the event and get triggered when it happens |
| triggerEveryTime | if true, the onChanged event of the observer will be triggered every time the observer is (re)created, as long as there is a value set. If false, it will only be triggered when the value is changed after the creation of the observer. |
