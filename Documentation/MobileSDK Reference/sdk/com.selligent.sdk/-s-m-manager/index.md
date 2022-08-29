//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)

# SMManager

[androidJvm]\
open class [SMManager](index.md)

Singleton object used to interact with the Selligent Mobile SDK.

## Functions

| Name | Summary |
|---|---|
| [areInAppMessagesEnabled](are-in-app-messages-enabled.md) | [androidJvm]<br>open fun [areInAppMessagesEnabled](are-in-app-messages-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This method tells if the management of In App messages is enabled or not |
| [areNotificationEnabled](are-notification-enabled.md) | [androidJvm]<br>open fun [areNotificationEnabled](are-notification-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This method tells if the reception of notifications is enabled or not |
| [areNotificationsAllowedByOS](are-notifications-allowed-by-o-s.md) | [androidJvm]<br>open fun [areNotificationsAllowedByOS](are-notifications-allowed-by-o-s.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This method tells if the notifications are allowed at OS level |
| [checkAndDisplayMessage](check-and-display-message.md) | [androidJvm]<br>open fun [checkAndDisplayMessage](check-and-display-message.md)(intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))<br>open fun [checkAndDisplayMessage](check-and-display-message.md)(intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), inAppMessageDisplay: [SMInAppMessageDisplay](../-s-m-in-app-message-display/index.md))<br>This method will check if there is a message to be displayed in the given intent and will display it. |
| [deleteInAppMessage](delete-in-app-message.md) | [androidJvm]<br>open fun [deleteInAppMessage](delete-in-app-message.md)(messageId: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>This method deletes one In-App Message. |
| [deleteInAppMessages](delete-in-app-messages.md) | [androidJvm]<br>open fun [deleteInAppMessages](delete-in-app-messages.md)(messageIds: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;)<br>This method deletes several In-App Messages at once. |
| [disableGeolocation](disable-geolocation.md) | [androidJvm]<br>open fun [disableGeolocation](disable-geolocation.md)()<br>Disables the geolocation functionality. |
| [disableInAppMessages](disable-in-app-messages.md) | [androidJvm]<br>open fun [disableInAppMessages](disable-in-app-messages.md)()<br>This method disables the management of &quot;in app&quot; messages. |
| [disableNotifications](disable-notifications.md) | [androidJvm]<br>open fun [disableNotifications](disable-notifications.md)()<br>This method disables the reception of push notifications from the server. |
| [displayLastReceivedRemotePushNotification](display-last-received-remote-push-notification.md) | [androidJvm]<br>open fun [displayLastReceivedRemotePushNotification](display-last-received-remote-push-notification.md)(activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html))<br>Display the latest received remote notification This is mostly used in conjunction with RemoteMessageDisplayType set to None |
| [displayMessage](display-message.md) | [androidJvm]<br>open fun [displayMessage](display-message.md)(messageId: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html))<br>Display the given message (remote or In App) whose id is given, like if clicking on the notification |
| [displayNotification](display-notification.md) | [androidJvm]<br>open fun [displayNotification](display-notification.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html))<br>This method is to be used only if you set [DoNotListenToThePush](../-s-m-settings/-do-not-listen-to-the-push.md) to true. |
| [enableGeolocation](enable-geolocation.md) | [androidJvm]<br>open fun [enableGeolocation](enable-geolocation.md)()<br>Enables the geolocation functionality. |
| [enableInAppMessages](enable-in-app-messages.md) | [androidJvm]<br>open fun [enableInAppMessages](enable-in-app-messages.md)(refreshType: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))<br>This method enables the management of &quot;in app&quot; messages. |
| [enableNotifications](enable-notifications.md) | [androidJvm]<br>open fun [enableNotifications](enable-notifications.md)()<br>This method enables the reception of push notifications from the server. |
| [executeButtonAction](execute-button-action.md) | [androidJvm]<br>open fun [executeButtonAction](execute-button-action.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), button: [SMNotificationButton](../-s-m-notification-button/index.md), message: [SMInAppMessage](../-s-m-in-app-message/index.md))<br>This method will execute the action attached to the given [SMNotificationButton](../-s-m-notification-button/index.md) of the given [SMInAppMessage](../-s-m-in-app-message/index.md). |
| [executeLinkAction](execute-link-action.md) | [androidJvm]<br>open fun [executeLinkAction](execute-link-action.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), link: [SMLink](../-s-m-link/index.md), content: [SMInAppContent](../-s-m-in-app-content/index.md))<br>This method will execute the action attached to the given [SMLink](../-s-m-link/index.md) of the given [SMInAppContent](../-s-m-in-app-content/index.md). |
| [getDeviceId](get-device-id.md) | [androidJvm]<br>open fun [getDeviceId](get-device-id.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>This methods returns the device id stored by the SDK after registering to the Selligent Mobile platform. |
| [getGCMToken](get-g-c-m-token.md) | [androidJvm]<br>open fun [getGCMToken](get-g-c-m-token.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>This methods returns the GCM token stored by the SDK. |
| [getInAppContents](get-in-app-contents.md) | [androidJvm]<br>open fun [getInAppContents](get-in-app-contents.md)(category: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), type: [SMContentType](../-s-m-content-type/index.md), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[SMInAppContent](../-s-m-in-app-content/index.md)&gt;<br>open fun [getInAppContents](get-in-app-contents.md)(category: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), type: [SMContentType](../-s-m-content-type/index.md), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), callbackEvent: [SMInAppContentReturn](../-s-m-in-app-content-return/index.md))<br>Gets the list of valid [SMInAppContent](../-s-m-in-app-content/index.md) for the given type and category. |
| [getInAppMessages](get-in-app-messages.md) | [androidJvm]<br>open fun [getInAppMessages](get-in-app-messages.md)(callbackEvent: [SMInAppMessageReturn](../-s-m-in-app-message-return/index.md))<br>Gets the list of all [SMInAppMessage](../-s-m-in-app-message/index.md) currently stored by the SDK, unfiltered. |
| [getInstance](get-instance.md) | [androidJvm]<br>open fun [getInstance](get-instance.md)(): [SMManager](index.md) |
| [getLastRemotePushNotification](get-last-remote-push-notification.md) | [androidJvm]<br>open fun [getLastRemotePushNotification](get-last-remote-push-notification.md)(): [HashMap](https://developer.android.com/reference/kotlin/java/util/HashMap.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;<br>Get the id and the title of the latest received remote notification This is mostly used in conjunction with RemoteMessageDisplayType set to None |
| [getNotificationIconColor](get-notification-icon-color.md) | [androidJvm]<br>open fun [getNotificationIconColor](get-notification-icon-color.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the icon color set by setNotificationIconColor. |
| [getNotificationLargeIcon](get-notification-large-icon.md) | [androidJvm]<br>open fun [getNotificationLargeIcon](get-notification-large-icon.md)(): [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)<br>Gets the icon set by setNotificationLargeIcon. |
| [getNotificationSmallIcon](get-notification-small-icon.md) | [androidJvm]<br>open fun [getNotificationSmallIcon](get-notification-small-icon.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>This returns the resource id set by setNotificationSmallIcon. |
| [getRemoteMessagesDisplayType](get-remote-messages-display-type.md) | [androidJvm]<br>open fun [getRemoteMessagesDisplayType](get-remote-messages-display-type.md)(): [SMRemoteMessageDisplayType](../-s-m-remote-message-display-type/index.md)<br>Gets the way remote messages are displayed when the app is in foreground. |
| [isExplanationNeededForPostNotificationPermission](is-explanation-needed-for-post-notification-permission.md) | [androidJvm]<br>open fun [isExplanationNeededForPostNotificationPermission](is-explanation-needed-for-post-notification-permission.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This method will return true if an explanation message needs to be displayed before requesting the post notification permission. |
| [isGeolocationEnabled](is-geolocation-enabled.md) | [androidJvm]<br>open fun [isGeolocationEnabled](is-geolocation-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tells if the geolocation is enabled or not. |
| [isPostNotificationPermissionGranted](is-post-notification-permission-granted.md) | [androidJvm]<br>open fun [isPostNotificationPermissionGranted](is-post-notification-permission-granted.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This method will tell if the permission to post notifications was granted or not. |
| [reload](reload.md) | [androidJvm]<br>open fun [reload](reload.md)(settings: [SMSettings](../-s-m-settings/index.md), callback: [SMCallback](../-s-m-callback/index.md))<br>This method is used in the special case of the Selligent demo app Parana and should not be needed. |
| [requestPostNotificationPermission](request-post-notification-permission.md) | [androidJvm]<br>open fun [requestPostNotificationPermission](request-post-notification-permission.md)(activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html), requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>This method will display the dialog asking the user for the notification permission. |
| [retrieveNotificationMessage](retrieve-notification-message.md) | [androidJvm]<br>open fun [retrieveNotificationMessage](retrieve-notification-message.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessageRetrieved: [OnSMNotificationMessageRetrieved](../-on-s-m-notification-message-retrieved/index.md))<br>It will trigger the [onSuccess](../-on-s-m-notification-message-retrieved/on-success.md) when the [SMNotificationMessage](../-s-m-notification-message/index.md) is retrieved from the intent. |
| [sendDeviceInfos](send-device-infos.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~open~~ ~~fun~~ [~~sendDeviceInfos~~](send-device-infos.md)~~(~~deviceInfos: [SMDeviceInfos](../-s-m-device-infos/index.md)~~)~~<br>This method will send a &quot;SetInfo&quot; event to the platform ONLY if the properties of the [SMDeviceInfos](../-s-m-device-infos/index.md) object changed since the last call |
| [sendSMEvent](send-s-m-event.md) | [androidJvm]<br>open fun [sendSMEvent](send-s-m-event.md)(event: [SMEvent](../-s-m-event/index.md))<br>Use this method to send an event to the Selligent platform. |
| [setApplication](set-application.md) | [androidJvm]<br>open fun [setApplication](set-application.md)(app: [Application](https://developer.android.com/reference/kotlin/android/app/Application.html))<br>This gives to the SDK a pointer to the Application instance. |
| [setButtonAsClicked](set-button-as-clicked.md) | [androidJvm]<br>open fun [setButtonAsClicked](set-button-as-clicked.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessage: [SMNotificationMessage](../-s-m-notification-message/index.md), @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationButton: [SMNotificationButton](../-s-m-notification-button/index.md))<br>It sends a ButtonClick event to the Selligent Mobile Platform. |
| [setFirebaseToken](set-firebase-token.md) | [androidJvm]<br>open fun [setFirebaseToken](set-firebase-token.md)(token: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>This method is to be used only if you set [DoNotFetchTheToken](../-s-m-settings/-do-not-fetch-the-token.md) to true. |
| [setInAppContentAsSeen](set-in-app-content-as-seen.md) | [androidJvm]<br>open fun [setInAppContentAsSeen](set-in-app-content-as-seen.md)(inAppContent: [SMInAppContent](../-s-m-in-app-content/index.md))<br>Set the given [SMInAppContent](../-s-m-in-app-content/index.md) as seen. |
| [setInAppMessageAsSeen](set-in-app-message-as-seen.md) | [androidJvm]<br>open fun [setInAppMessageAsSeen](set-in-app-message-as-seen.md)(inAppMessage: [SMInAppMessage](../-s-m-in-app-message/index.md))<br>Set the given [SMInAppMessage](../-s-m-in-app-message/index.md) as seen. |
| [setInAppMessageAsUnseen](set-in-app-message-as-unseen.md) | [androidJvm]<br>open fun [setInAppMessageAsUnseen](set-in-app-message-as-unseen.md)(inAppMessage: [SMInAppMessage](../-s-m-in-app-message/index.md))<br>Set the given [SMInAppMessage](../-s-m-in-app-message/index.md) as unseen. |
| [setNotificationIconColor](set-notification-icon-color.md) | [androidJvm]<br>open fun [setNotificationIconColor](set-notification-icon-color.md)(argb: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>This allows the SDK to set a specific color to the icon for the notifications. |
| [setNotificationLargeIcon](set-notification-large-icon.md) | [androidJvm]<br>open fun [setNotificationLargeIcon](set-notification-large-icon.md)(iconResource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>This allows the SDK to use a specific icon for the notifications. |
| [setNotificationMessageAsReceived](set-notification-message-as-received.md) | [androidJvm]<br>open fun [setNotificationMessageAsReceived](set-notification-message-as-received.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessage: [SMNotificationMessage](../-s-m-notification-message/index.md))<br>It sends a PushReceived event to the Selligent Mobile Platform. |
| [setNotificationMessageAsSeen](set-notification-message-as-seen.md) | [androidJvm]<br>open fun [setNotificationMessageAsSeen](set-notification-message-as-seen.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)notificationMessage: [SMNotificationMessage](../-s-m-notification-message/index.md))<br>It sends a PushOpened event to the Selligent Mobile Platform. |
| [setNotificationSmallIcon](set-notification-small-icon.md) | [androidJvm]<br>open fun [setNotificationSmallIcon](set-notification-small-icon.md)(iconResource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>This allows the SDK to use a specific icon for the notifications. |
| [start](start.md) | [androidJvm]<br>open fun [start](start.md)(settings: [SMSettings](../-s-m-settings/index.md))<br>open fun [start](start.md)(settings: [SMSettings](../-s-m-settings/index.md), application: [Application](https://developer.android.com/reference/kotlin/android/app/Application.html))<br>Mandatory method used to setup the Selligent Mobile SDK. |

## Properties

| Name | Summary |
|---|---|
| [BROADCAST_DATA_BUTTON](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-b-u-t-t-o-n.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_DATA_BUTTON~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-b-u-t-t-o-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a key to retrieve an object inside an intent Use this key to retrive the object [SMNotificationButton](../-s-m-notification-button/index.md) from the intent received from the broadcast [BROADCAST_EVENT_BUTTON_CLICKED](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md). |
| [BROADCAST_DATA_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-g-c-m_-t-o-k-e-n.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_DATA_GCM_TOKEN~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-g-c-m_-t-o-k-e-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a key to retrieve an object inside an intent Use this key to retrieve the GCM token from the intent received from the broadcast [BROADCAST_EVENT_RECEIVED_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md). |
| [BROADCAST_DATA_IN_APP_CONTENTS](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_DATA_IN_APP_CONTENTS~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a key to retrieve an object inside an intent Use this key to retrieve an dictionary containing the number of contents for each category from the broadcast [BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md). |
| [BROADCAST_DATA_IN_APP_MESSAGES](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-m-e-s-s-a-g-e-s.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_DATA_IN_APP_MESSAGES~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-m-e-s-s-a-g-e-s.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a key to retrieve an object inside an intent Use this key to retrieve an array of [SMInAppMessage](../-s-m-in-app-message/index.md) from the intent received from the broadcast [BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md). |
| [BROADCAST_EVENT_BUTTON_CLICKED](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_EVENT_BUTTON_CLICKED~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a broadcast name you can listen to. |
| [BROADCAST_EVENT_RECEIVED_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_EVENT_RECEIVED_GCM_TOKEN~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a broadcast name you can listen to. |
| [BROADCAST_EVENT_RECEIVED_IN_APP_CONTENTS](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_EVENT_RECEIVED_IN_APP_CONTENTS~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a broadcast name you can listen to. |
| [BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a broadcast name you can listen to. |
| [BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-m-i-s-s_-n-o-t-i-f-i-c-a-t-i-o-n.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-m-i-s-s_-n-o-t-i-f-i-c-a-t-i-o-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a broadcast name you can listen to. |
| [BROADCAST_EVENT_WILL_DISPLAY_NOTIFICATION](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-p-l-a-y_-n-o-t-i-f-i-c-a-t-i-o-n.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~val~~ [~~BROADCAST_EVENT_WILL_DISPLAY_NOTIFICATION~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-p-l-a-y_-n-o-t-i-f-i-c-a-t-i-o-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>String representing a broadcast name you can listen to. |
| [DEBUG](-d-e-b-u-g.md) | [androidJvm]<br>open var [DEBUG](-d-e-b-u-g.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>When true, different actions and informations will be logged by the SDK and visible in the logcat in Android Studio (tag &quot;SDK&quot;). |
| [MAIN_ACTIVITY](-m-a-i-n_-a-c-t-i-v-i-t-y.md) | [androidJvm]<br>open var [MAIN_ACTIVITY](-m-a-i-n_-a-c-t-i-v-i-t-y.md): [Class](https://developer.android.com/reference/kotlin/java/lang/Class.html)&lt;out [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html)&gt;<br>The main activity of your app. |
| [NOTIFICATION_ACTIVITY](-n-o-t-i-f-i-c-a-t-i-o-n_-a-c-t-i-v-i-t-y.md) | [androidJvm]<br>open var [NOTIFICATION_ACTIVITY](-n-o-t-i-f-i-c-a-t-i-o-n_-a-c-t-i-v-i-t-y.md): [Class](https://developer.android.com/reference/kotlin/java/lang/Class.html)&lt;out [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html)&gt;<br>The activity that will be called when opening a notification. |
| [observerManager](observer-manager.md) | [androidJvm]<br>open val [observerManager](observer-manager.md): [SMObserverManager](../-s-m-observer-manager/index.md) |
| [VERSION_LIB](-v-e-r-s-i-o-n_-l-i-b.md) | [androidJvm]<br>val [VERSION_LIB](-v-e-r-s-i-o-n_-l-i-b.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>* The version of the Selligent Mobile SDK library |