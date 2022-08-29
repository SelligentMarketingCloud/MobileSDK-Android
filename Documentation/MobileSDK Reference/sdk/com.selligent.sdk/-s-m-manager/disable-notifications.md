//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[disableNotifications](disable-notifications.md)

# disableNotifications

[androidJvm]\
open fun [disableNotifications](disable-notifications.md)()

This method disables the reception of push notifications from the server. It sends an &quot;opt-out&quot; message to the web service to tell it to stop sending push notifications to the device. Any still received will be ignored by the SDK.
