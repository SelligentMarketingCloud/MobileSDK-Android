//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMObserverManager](index.md)/[observeDeviceId](observe-device-id.md)

# observeDeviceId

[androidJvm]\

@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)

open fun [observeDeviceId](observe-device-id.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)observer: [Observer](https://developer.android.com/reference/kotlin/androidx/lifecycle/Observer.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;)

Use this method to get notified when the SDK receives the device id from the Marigold Engage Mobile platform. It must be called on the main thread. Observing using this method will trigger the onChanged event of the observer only when the value changes after the observer is created. If there is already a value at that moment, the event will not get triggered. To change that behaviour, use the overload [observeToken](observe-token.md)

#### Parameters

androidJvm

| | |
|---|---|
| lifecycleOwner | The LifecycleOwner that will be used to automatically start and stop listening. Most of the time, it will be the Activity you are in. |
| observer | The Observer that will listen to the event and get triggered when it happens |

[androidJvm]\

@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)

open fun [observeDeviceId](observe-device-id.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)observer: [Observer](https://developer.android.com/reference/kotlin/androidx/lifecycle/Observer.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, triggerEveryTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Use this method to get notified when the SDK receives the device id from the Marigold Engage Mobile platform. It must be called on the main thread.

#### Parameters

androidJvm

| | |
|---|---|
| lifecycleOwner | The LifecycleOwner that will be used to automatically start and stop listening. Most of the time, it will be the Activity you are in. |
| observer | The Observer that will listen to the event and get triggered when it happens |
| triggerEveryTime | if true, the onChanged event of the observer will be triggered every time the observer is (re)created, as long as there is a value set. If false, it will only be triggered when the value is changed after the creation of the observer. |
