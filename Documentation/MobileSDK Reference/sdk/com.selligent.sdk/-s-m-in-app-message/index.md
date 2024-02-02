//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMInAppMessage](index.md)

# SMInAppMessage

[androidJvm]\
open class [SMInAppMessage](index.md) : InternalInAppMessage, [Externalizable](https://developer.android.com/reference/kotlin/java/io/Externalizable.html)

An In App message

## Constructors

| | |
|---|---|
| [SMInAppMessage](-s-m-in-app-message.md) | [androidJvm]<br>constructor()constructor(json: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)) |

## Properties

| Name | Summary |
|---|---|
| [id](id.md) | [androidJvm]<br>open var [id](id.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [receptionDate](../-s-m-notification-message/index.md#-931209582%2FProperties%2F462465411) | [androidJvm]<br>open val [receptionDate](../-s-m-notification-message/index.md#-931209582%2FProperties%2F462465411): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [title](title.md) | [androidJvm]<br>open var [title](title.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [androidJvm]<br>open fun [equals](equals.md)(otherMessage: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares this instance with the specified object and indicates if they are equal. |
| [getBody](get-body.md) | [androidJvm]<br>open fun [getBody](get-body.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the body of the SMInAppMessage |
| [getButtons](get-buttons.md) | [androidJvm]<br>open fun [getButtons](get-buttons.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMNotificationButton](../-s-m-notification-button/index.md)&gt;<br>Gets the buttons of the SMInAppMessage |
| [getCreationDate](../-s-m-notification-message/index.md#1504688716%2FFunctions%2F462465411) | [androidJvm]<br>open fun [getCreationDate](../-s-m-notification-message/index.md#1504688716%2FFunctions%2F462465411)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the creation date of the notification |
| [getExpirationDate](../-s-m-notification-message/index.md#-355182212%2FFunctions%2F462465411) | [androidJvm]<br>open fun [getExpirationDate](../-s-m-notification-message/index.md#-355182212%2FFunctions%2F462465411)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the expiration date of the notification |
| [getId](get-id.md) | [androidJvm]<br>open fun [getId](get-id.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the id of the SMInAppMessage |
| [getMarkers](get-markers.md) | [androidJvm]<br>open fun [getMarkers](get-markers.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMMapMarker](../-s-m-map-marker/index.md)&gt;<br>Gets the list of the markers for an In-app message of type Map |
| [getTitle](get-title.md) | [androidJvm]<br>open fun [getTitle](get-title.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the title of the SMInAppMessage |
| [getType](get-type.md) | [androidJvm]<br>open fun [getType](get-type.md)(): [SMMessageType](../-s-m-message-type/index.md)<br>Gets the type of the SMInAppMessage |
| [hasBeenSeen](has-been-seen.md) | [androidJvm]<br>open fun [hasBeenSeen](has-been-seen.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tells if the SMInAppContent has already been seen or not. |
| [hashCode](hash-code.md) | [androidJvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns an integer hash code for this object. |
| [readExternal](read-external.md) | [androidJvm]<br>open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object. |
| [writeExternal](write-external.md) | [androidJvm]<br>open fun [writeExternal](write-external.md)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object. |
