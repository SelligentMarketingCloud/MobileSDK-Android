//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEvent](index.md)

# SMEvent

[androidJvm]\
open class [SMEvent](index.md) : [Externalizable](https://developer.android.com/reference/kotlin/java/io/Externalizable.html)

Object used to send a custom event to the Selligent platform with SMManager.sendEvent.

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMManager](../-s-m-manager/send-s-m-event.md) |  |

## Constructors

| | |
|---|---|
| [SMEvent](-s-m-event.md) | [androidJvm]<br>open fun [SMEvent](-s-m-event.md)()<br>Constructs an SMEvent object without data and callback |
| [SMEvent](-s-m-event.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~open~~ ~~fun~~ [~~SMEvent~~](-s-m-event.md)~~(~~data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md)~~)~~<br>Constructs an SMEvent object with the following: |
| [SMEvent](-s-m-event.md) | [androidJvm]<br>open fun [SMEvent](-s-m-event.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))<br>Constructs an SMEvent object with the following: |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [androidJvm]<br>open fun [equals](equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares this instance with the specified object and indicates if they are equal. |
| [hashCode](hash-code.md) | [androidJvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns an integer hash code for this object. |
| [readExternal](read-external.md) | [androidJvm]<br>open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object. |
| [writeExternal](write-external.md) | [androidJvm]<br>open fun [writeExternal](write-external.md)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object. |

## Properties

| Name | Summary |
|---|---|
| [Callback](-callback.md) | [androidJvm]<br>open var [Callback](-callback.md): [SMCallback](../-s-m-callback/index.md)<br>A SMCallback object containing code to execute after the message is sent |
| [Data](-data.md) | [androidJvm]<br>open var [Data](-data.md): [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;<br>Custom data |
