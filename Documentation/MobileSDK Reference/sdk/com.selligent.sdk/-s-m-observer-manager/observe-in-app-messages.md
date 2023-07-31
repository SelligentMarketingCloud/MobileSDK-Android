//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMObserverManager](index.md)/[observeInAppMessages](observe-in-app-messages.md)

# observeInAppMessages

[androidJvm]\

@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)

open fun [observeInAppMessages](observe-in-app-messages.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)observer: [Observer](https://developer.android.com/reference/kotlin/androidx/lifecycle/Observer.html)&lt;[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMInAppMessage](../-s-m-in-app-message/index.md)&gt;&gt;)

Use this method to get notified when new In-App messages were fetched. It replaces the broadcast BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE. It must be called on the main thread. Observing using this method will trigger the onChanged event of the observer only when the value changes after the observer is created. If there is already a value at that moment, the event will not get triggered. To change that behaviour, use the overload [observeInAppMessages](observe-in-app-messages.md)

#### Parameters

androidJvm

| | |
|---|---|
| lifecycleOwner | The LifecycleOwner that will be used to automatically start and stop listening. Most of the time, it will be the Activity you are in. |
| observer | The Observer that will listen to the event and get triggered when it happens |

[androidJvm]\

@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)

open fun [observeInAppMessages](observe-in-app-messages.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)observer: [Observer](https://developer.android.com/reference/kotlin/androidx/lifecycle/Observer.html)&lt;[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMInAppMessage](../-s-m-in-app-message/index.md)&gt;&gt;, triggerEveryTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Use this method to get notified when new In-App messages were fetched. It replaces the broadcast BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE. It must be called on the main thread.

#### Parameters

androidJvm

| | |
|---|---|
| lifecycleOwner | The LifecycleOwner that will be used to automatically start and stop listening. Most of the time, it will be the Activity you are in. |
| observer | The Observer that will listen to the event and get triggered when it happens |
| triggerEveryTime | if true, the onChanged event of the observer will be triggered every time the observer is (re)created, as long as there is a value set. If false, it will only be triggered when the value is changed after the creation of the observer. |
