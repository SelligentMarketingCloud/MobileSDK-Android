//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[requestPostNotificationPermission](request-post-notification-permission.md)

# requestPostNotificationPermission

[androidJvm]\
open fun [requestPostNotificationPermission](request-post-notification-permission.md)(activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html), requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

This method will display the dialog asking the user for the notification permission. It should be called at an appropriate time in the app workflow. The dialog will only be called when running on Android 13 (API 33) and higher. Nothing will happen for older versions (as the permission did not exist).

#### Parameters

androidJvm

| | |
|---|---|
| activity | The current activity |
| requestCode | Application specific request code to match with a result |
