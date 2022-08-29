//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEvent](index.md)/[SMEvent](-s-m-event.md)

# SMEvent

[androidJvm]\
open fun [SMEvent](-s-m-event.md)()

Constructs an SMEvent object without data and callback

[androidJvm]\

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~open~~ ~~fun~~ [~~SMEvent~~](-s-m-event.md)~~(~~data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md)~~)~~

Constructs an SMEvent object with the following:

#### Deprecated

since 4.0, use [SMEvent](-s-m-event.md) instead

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMCallback](../-s-m-callback/index.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| data | a Hashtable<String, String> containing the custom data |
| callback | a SMCallback object containing code to execute after the message is sent |

[androidJvm]\
open fun [SMEvent](-s-m-event.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))

Constructs an SMEvent object with the following:

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMCallback](../-s-m-callback/index.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| name | the name of the event |
| data | a Hashtable<String, String> containing the custom data |
| callback | a SMCallback object containing code to execute after the message is sent |
