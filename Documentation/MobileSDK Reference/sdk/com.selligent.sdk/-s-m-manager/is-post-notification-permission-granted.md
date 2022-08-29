//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[isPostNotificationPermissionGranted](is-post-notification-permission-granted.md)

# isPostNotificationPermissionGranted

[androidJvm]\
open fun [isPostNotificationPermissionGranted](is-post-notification-permission-granted.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

This method will tell if the permission to post notifications was granted or not. Do not confuse this method with the above [areNotificationsAllowedByOS](are-notifications-allowed-by-o-s.md). If the permission is not granted, both will return false. If the permission is granted but the notification channel id deactivated, then this method will return true while [areNotificationsAllowedByOS](are-notifications-allowed-by-o-s.md) will return false. The check is only performed when running on Android 13 (API 33) and higher. It will always return true for older versions (as the permission did not exist).

#### Return

true if was granted, false otherwise
