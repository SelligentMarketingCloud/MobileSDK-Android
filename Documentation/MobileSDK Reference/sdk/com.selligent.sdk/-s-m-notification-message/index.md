//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMNotificationMessage](index.md)

# SMNotificationMessage

[androidJvm]\
open class [SMNotificationMessage](index.md) : NotificationMessage

A notification message.

## Constructors

| | |
|---|---|
| [SMNotificationMessage](-s-m-notification-message.md) | [androidJvm]<br>open fun [SMNotificationMessage](-s-m-notification-message.md)() |

## Functions

| Name | Summary |
|---|---|
| [getCreationDate](get-creation-date.md) | [androidJvm]<br>open fun [getCreationDate](get-creation-date.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the creation date of the notification |
| [getExpirationDate](get-expiration-date.md) | [androidJvm]<br>open fun [getExpirationDate](get-expiration-date.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the expiration date of the notification |
| [getIAMBody](get-i-a-m-body.md) | [androidJvm]<br>open fun [getIAMBody](get-i-a-m-body.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the body of the In-app message linked to the notification |
| [getIAMButtons](get-i-a-m-buttons.md) | [androidJvm]<br>open fun [getIAMButtons](get-i-a-m-buttons.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMNotificationButton](../-s-m-notification-button/index.md)&gt;<br>Gets the buttons of the In-app message linked to the notification |
| [getIAMMarkers](get-i-a-m-markers.md) | [androidJvm]<br>open fun [getIAMMarkers](get-i-a-m-markers.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMMapMarker](../-s-m-map-marker/index.md)&gt;<br>Gets the list of the markers for the In-app message linked to the notification |
| [getIAMTitle](get-i-a-m-title.md) | [androidJvm]<br>open fun [getIAMTitle](get-i-a-m-title.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the title of the In-app message linked to the notification |
| [getIAMType](get-i-a-m-type.md) | [androidJvm]<br>open fun [getIAMType](get-i-a-m-type.md)(): [SMMessageType](../-s-m-message-type/index.md)<br>Gets the type of the In-App message linked to the notification |
| [getId](get-id.md) | [androidJvm]<br>open fun [getId](get-id.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the id of the notification |
| [getMainAction](get-main-action.md) | [androidJvm]<br>open fun [getMainAction](get-main-action.md)(): [SMNotificationButton](../-s-m-notification-button/index.md)<br>Gets the main action of the notification |
| [getMediaType](get-media-type.md) | [androidJvm]<br>open fun [getMediaType](get-media-type.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the type of the media to display in the notification. |
| [getMediaUrl](get-media-url.md) | [androidJvm]<br>open fun [getMediaUrl](get-media-url.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the URL of the media to display in the notification |
| [getNotificationBody](get-notification-body.md) | [androidJvm]<br>open fun [getNotificationBody](get-notification-body.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the body of the notification |
| [getNotificationButtons](get-notification-buttons.md) | [androidJvm]<br>open fun [getNotificationButtons](get-notification-buttons.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMNotificationButton](../-s-m-notification-button/index.md)&gt;<br>Gets the buttons of the notification |
| [getNotificationTitle](get-notification-title.md) | [androidJvm]<br>open fun [getNotificationTitle](get-notification-title.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the title of the notification |
| [getReceptionDate](get-reception-date.md) | [androidJvm]<br>open fun [getReceptionDate](get-reception-date.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the reception date of the notification |
| [readExternal](index.md#946941663%2FFunctions%2F462465411) | [androidJvm]<br>open fun [readExternal](index.md#946941663%2FFunctions%2F462465411)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>abstract fun [readExternal](index.md#-1306664077%2FFunctions%2F462465411)(p: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html)) |
| [writeExternal](index.md#-1742959745%2FFunctions%2F462465411) | [androidJvm]<br>open fun [writeExternal](index.md#-1742959745%2FFunctions%2F462465411)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>abstract fun [writeExternal](index.md#1500408595%2FFunctions%2F462465411)(p: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html)) |
