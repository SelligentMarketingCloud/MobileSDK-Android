//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[getLastRemotePushNotification](get-last-remote-push-notification.md)

# getLastRemotePushNotification

[androidJvm]\
open fun [getLastRemotePushNotification](get-last-remote-push-notification.md)(): [HashMap](https://developer.android.com/reference/kotlin/java/util/HashMap.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;

Get the id and the title of the latest received remote notification This is mostly used in conjunction with RemoteMessageDisplayType set to None

#### Return

a HashMap containing the &quot;id&quot; and &quot;title&quot; of the last remote notification

#### Deprecated

since 4.0.1, use [retrieveLastReceivedNotificationContent](retrieve-last-received-notification-content.md) instead
