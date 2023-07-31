//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[isExplanationNeededForPostNotificationPermission](is-explanation-needed-for-post-notification-permission.md)

# isExplanationNeededForPostNotificationPermission

[androidJvm]\
open fun [isExplanationNeededForPostNotificationPermission](is-explanation-needed-for-post-notification-permission.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

This method will return true if an explanation message needs to be displayed before requesting the post notification permission. The check is only performed when running on Android 13 (API 33) and higher. It will always return false for older versions (as the permission did not exist).

#### Return

true if an explanation is needed, false otherwise

#### Parameters

androidJvm

| | |
|---|---|
| activity | the Activity from which you call this method |
