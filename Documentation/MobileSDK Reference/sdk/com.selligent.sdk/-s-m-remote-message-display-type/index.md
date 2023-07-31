//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMRemoteMessageDisplayType](index.md)

# SMRemoteMessageDisplayType

[androidJvm]\
enum [SMRemoteMessageDisplayType](index.md)

List the different possibilities to display a remote message received while the app is in foreground - Automatic: the message is automatically displayed - Notification: a notification is created, the user needs to click on it to display the message - None: nothing is done, the message is not displayed, it is up to the app to display it (cf. [getLastRemotePushNotification](../-s-m-manager/get-last-remote-push-notification.md), [displayLastReceivedRemotePushNotification](../-s-m-manager/display-last-received-remote-push-notification.md))

## Entries

| | |
|---|---|
| [Automatic](-automatic/index.md) | [androidJvm]<br>[Automatic](-automatic/index.md) |
| [Notification](-notification/index.md) | [androidJvm]<br>[Notification](-notification/index.md) |
| [None](-none/index.md) | [androidJvm]<br>[None](-none/index.md) |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>open fun [valueOf](value-of.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [SMRemoteMessageDisplayType](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMRemoteMessageDisplayType](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. This method may be used to iterate over the constants. |
