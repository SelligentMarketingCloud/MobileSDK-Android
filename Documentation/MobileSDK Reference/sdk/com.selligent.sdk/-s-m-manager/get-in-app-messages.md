//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[getInAppMessages](get-in-app-messages.md)

# getInAppMessages

[androidJvm]\
open fun [getInAppMessages](get-in-app-messages.md)(callbackEvent: [SMInAppMessageReturn](../-s-m-in-app-message-return/index.md))

Gets the list of all [SMInAppMessage](../-s-m-in-app-message/index.md) currently stored by the SDK, unfiltered. Use this method if you want to display the In-App messages yourself. Note: the messages retrieved using this method are the exact content of the In-App message cache. If you started the SDK with the value None for SMSettings.ClearCacheIntervalValue, it means there is no cache for the In-App messages and, therefore, this will return an empty array. In that case, you must rely only on the observer to retrieve the In-App messages.

## Parameters

androidJvm

| | |
|---|---|
| callbackEvent | The event that will be called when the messages are retrieved. It will be passed an [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html) of [SMInAppMessage](../-s-m-in-app-message/index.md) |
