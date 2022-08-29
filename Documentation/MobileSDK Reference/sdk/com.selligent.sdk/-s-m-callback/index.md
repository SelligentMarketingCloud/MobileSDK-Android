//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMCallback](index.md)

# SMCallback

[androidJvm]\
interface [SMCallback](index.md)

This allows to write codes that will be executed after an event is sent to the Selligent platform

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMEvent](../-s-m-event/index.md) |  |
| [com.selligent.sdk.SMManager](../-s-m-manager/send-s-m-event.md) |  |

## Functions

| Name | Summary |
|---|---|
| [onError](on-error.md) | [androidJvm]<br>abstract fun [onError](on-error.md)(httpResponseCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), exception: [Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html))<br>Event triggered when an error occured while sending the SMEvent |
| [onSuccess](on-success.md) | [androidJvm]<br>abstract fun [onSuccess](on-success.md)(result: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Event triggered when the SMEvent was sent successfully. |
