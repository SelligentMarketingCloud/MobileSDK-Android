//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEventUserRegister](index.md)

# SMEventUserRegister

open class [SMEventUserRegister](index.md) : SMEventUser

Object used to send a &quot;register&quot; event to the Marigold Engage platform with SMManager.sendEvent.

#### See also

| |
|---|
| [SMManager](../-s-m-manager/send-s-m-event.md) |

## Constructors

| | |
|---|---|
| [SMEventUserRegister](-s-m-event-user-register.md) | [androidJvm]<br>constructor()constructor(profileId: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))<br>Constructs a new SMEventUserRegister<br>constructor(data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))<br>Constructs a new SMEventUserRegister |

## Properties

| Name | Summary |
|---|---|
| [Callback](../-s-m-event/-callback.md) | [androidJvm]<br>open var [Callback](../-s-m-event/-callback.md): [SMCallback](../-s-m-callback/index.md)<br>A SMCallback object containing code to execute after the message is sent |
| [Data](../-s-m-event/-data.md) | [androidJvm]<br>open var [Data](../-s-m-event/-data.md): [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;<br>Custom data |
| [Email](../-s-m-event-user-unregister/index.md#1053791770%2FProperties%2F462465411) | [androidJvm]<br>open var [~~Email~~](../-s-m-event-user-unregister/index.md#1053791770%2FProperties%2F462465411): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [Profile](../-s-m-event-user-unregister/index.md#-952461715%2FProperties%2F462465411) | [androidJvm]<br>open var [Profile](../-s-m-event-user-unregister/index.md#-952461715%2FProperties%2F462465411): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Functions

| Name | Summary |
|---|---|
| [equals](../-s-m-event-user-unregister/index.md#1419080370%2FFunctions%2F462465411) | [androidJvm]<br>open fun [equals](../-s-m-event-user-unregister/index.md#1419080370%2FFunctions%2F462465411)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares this instance with the specified object and indicates if they are equal. |
| [hashCode](../-s-m-event-user-unregister/index.md#-254228727%2FFunctions%2F462465411) | [androidJvm]<br>open fun [hashCode](../-s-m-event-user-unregister/index.md#-254228727%2FFunctions%2F462465411)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns an integer hash code for this object. |
| [readExternal](../-s-m-event-user-unregister/index.md#-1646240016%2FFunctions%2F462465411) | [androidJvm]<br>open fun [readExternal](../-s-m-event-user-unregister/index.md#-1646240016%2FFunctions%2F462465411)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object.<br>[androidJvm]<br>abstract fun [readExternal](../-s-m-notification-message/index.md#-1306664077%2FFunctions%2F462465411)(p: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html)) |
| [writeExternal](../-s-m-event-user-unregister/index.md#1585445712%2FFunctions%2F462465411) | [androidJvm]<br>open fun [writeExternal](../-s-m-event-user-unregister/index.md#1585445712%2FFunctions%2F462465411)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object.<br>[androidJvm]<br>abstract fun [writeExternal](../-s-m-notification-message/index.md#1500408595%2FFunctions%2F462465411)(p: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html)) |
