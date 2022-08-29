//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEventUserUnregister](index.md)

# SMEventUserUnregister

[androidJvm]\
open class [SMEventUserUnregister](index.md) : SMEventUser

Object used to send an &quot;unregister&quot; event to the Selligent platform with SMManager.sendEvent.

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMManager](../-s-m-manager/send-s-m-event.md) |  |

## Constructors

| | |
|---|---|
| [SMEventUserUnregister](-s-m-event-user-unregister.md) | [androidJvm]<br>open fun [SMEventUserUnregister](-s-m-event-user-unregister.md)() |
| [SMEventUserUnregister](-s-m-event-user-unregister.md) | [androidJvm]<br>open fun [SMEventUserUnregister](-s-m-event-user-unregister.md)(profileId: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))<br>Constructs a new SMEventUserUnregister |
| [SMEventUserUnregister](-s-m-event-user-unregister.md) | [androidJvm]<br>open fun [SMEventUserUnregister](-s-m-event-user-unregister.md)(data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))<br>Constructs a new SMEventUserUnregister |

## Functions

| Name | Summary |
|---|---|
| [equals](index.md#1419080370%2FFunctions%2F462465411) | [androidJvm]<br>open fun [equals](index.md#1419080370%2FFunctions%2F462465411)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares this instance with the specified object and indicates if they are equal. |
| [hashCode](index.md#-254228727%2FFunctions%2F462465411) | [androidJvm]<br>open fun [hashCode](index.md#-254228727%2FFunctions%2F462465411)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns an integer hash code for this object. |
| [readExternal](index.md#-1646240016%2FFunctions%2F462465411) | [androidJvm]<br>open fun [readExternal](index.md#-1646240016%2FFunctions%2F462465411)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object.<br>[androidJvm]<br>abstract fun [readExternal](../-s-m-notification-message/index.md#-1306664077%2FFunctions%2F462465411)(p: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html)) |
| [writeExternal](index.md#1585445712%2FFunctions%2F462465411) | [androidJvm]<br>open fun [writeExternal](index.md#1585445712%2FFunctions%2F462465411)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object.<br>[androidJvm]<br>abstract fun [writeExternal](../-s-m-notification-message/index.md#1500408595%2FFunctions%2F462465411)(p: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html)) |

## Properties

| Name | Summary |
|---|---|
| [Callback](../-s-m-event/-callback.md) | [androidJvm]<br>open var [Callback](../-s-m-event/-callback.md): [SMCallback](../-s-m-callback/index.md)<br>A SMCallback object containing code to execute after the message is sent |
| [Data](../-s-m-event/-data.md) | [androidJvm]<br>open var [Data](../-s-m-event/-data.md): [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;<br>Custom data |
| [Email](index.md#1053791770%2FProperties%2F462465411) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~open~~ ~~var~~ [~~Email~~](index.md#1053791770%2FProperties%2F462465411)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [Profile](index.md#-952461715%2FProperties%2F462465411) | [androidJvm]<br>open var [Profile](index.md#-952461715%2FProperties%2F462465411): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |