//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMCallback](index.md)/[onError](on-error.md)

# onError

[androidJvm]\
abstract fun [onError](on-error.md)(httpResponseCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), exception: [Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html))

Event triggered when an error occured while sending the SMEvent

## Parameters

androidJvm

| | |
|---|---|
| httpResponseCode | the code of the error (404, 500, etc.) |
| exception | the Exception thrown by the web service call |
