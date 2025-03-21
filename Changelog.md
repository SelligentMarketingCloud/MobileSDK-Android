# SDK Changelog

- Version 4.6.1
	- Fixed a bug where the In-App title is empty

- Version 4.6.0
	- Ensured compatibility with Android 15 (API 35)
	- Upgraded Gradle Plugin to 8.2.2

- Version 4.5.0
	- Added support of Jetpack Compose when displaying a dialog
	- Added robustness in some exception management

- Version 4.4.1
	- Fixed bug where the creation and expiration date where missing on the notification and in-app message objects
	- Replaced Selligent by Marigold Engage in the documentation

- Version 4.4.0
	- Ensured compatibility with Android 14 (API 34)
	- Upgraded Gradle Plugin to 8.1.0

- Version 4.3.0
	- Increased minSdkVersion to 21 (Android 5.0)
	- Fixed a bug where some dependencies were falsely detected as missing when the app is minified, 
	  preventing some functionality to work correctly.

- Version 4.2.1
	- Fixed a bug causing an exception when redisplaying a rich push notification
	- Fixed a bug causing an empty notification to appear when redisplaying a notification although none had been received yet.
	- Added robustness when deserializing events

- Version 4.2.0
	- Removed all references to PlotProject
	- Deprecated all geolocation related methods

- Version 4.1.0
	- Renamed some methods to be in sync with the IOS SDK
	- Added a method to redisplay the last received notification
	- Added an observer to be warned when a push is received (while the app is in foreground)

- Version 4.0.3
	- Corrected a bug where the "seen" and "deleted" properties of an In-app message could be wrongly overwritten
	- Improved overal robustness

- Version 4.0.1
	- Corrected a bug where the notification is not displayed when the SDK is given a custom channel id.
	- Improved the enableNotification() in case the notification permission changed

- Version 4.0.0
	- Removed several method and classes that had been deprecated for a while
	- Replaced the AsyncTasks by Kotlin coroutines
	- Added helper methods to manage the notification permission
	- Corrected a bug where unsent events were not retried when the app was awaken by a push notification.

- Version 3.10.1
	- Corrected a bug where the “seen” property was not saved after calling setInappMessageAsSeen().

- Version 3.10.0
	- Added the support to “simple button” in a notification, that will trigger the sending of a button click event without opening the app.

- Version 3.9.0
	- Added the possibility to use a pre-existing notification channel and/or to specify its name and description.
	- Added the possibility to display the dialog with rounded corners.

- Version 3.8.3
	- SDK available on Maven Central.

- Version 3.8.2
	- Fixed a bug preventing the display of a rich push when the app is minified

- Version 3.8.1
	- Fixed a bug making the Huawei dependencies mandatory when they should be optional

- Version 3.8.0
	- Added support for Huawei Mobile Services (HMS). Now, when our SDK is in an app running on a device that doesn’t have Google Play Services but has Huawei Services, it will use those to retrieve a token and listen to the push notifications. This means the SDK will work in an Android app running on a Huawei device without Google Play Services (Android or HarmonyOS). It will not, however, work in a native HarmonyOS app.
	- NOTE: Sending push through Huawei Services is only supported by the Engage Mobile Platform for customers using SDC. Ask your Engage contact for more information about SDC.

- Version 3.7.0
	- Added support to Android 12 (API 31)
	- Added a check when starting the SDK to verify if the notifications were enabled/disabled in the OS settings and send the information to the Engage Mobile platform if needed.
	- Enabled DOM storage for the Web views
	- Exposed the push notification payload and added helper methods to manage the events (cf. Manual management of the push).
- Version 3.6.0
	- Added an overload of checkAndDisplayMessage to allow you to display the In-App message linked to a push yourself.
	- Added AddInAppMessageFromPushToInAppMessageList to SMSettings to allow the In-App message linked to a push to be stored with the other In-App messages.
	- Added WebViewNavigationOverride to allow you to intercept the links clicked in a WebView of an In-App Message and decide if the navigation will proceed or not.
	- Added method and observer to retrieve the device id.
	- Corrected a bug preventing onNewIntent to be called.
	- Different code clean-up/refactoring.
- Version 3.5.1
	- Corrected bug where SMMessageType was not public
- Version 3.5.0
	- Small modification to display the image from a rich push as a thumbnail when the notification is collapsed.
	- Added a method to delete the In-App messages and another to mark them as unread.
	- Some bug corrections
	- Clean-up of obsolete code.
- Version 3.4.0
	- Added properties on SMInAppMessage and methods on SMManager to give access to the full payload of the In-App messages, allowing the possibility to display the In-App messages without the SDK.
	- Added a property on SMSettings to prevent the SDK from automatically enabling the notifications once the token is retrieved.
- Version 3.3.0
	- Added Android 11 support (API 30)
	- Corrected a problem when an In-App message was displayed from an activity having its launchMode set to "singleInstance"
- Version 3.2.0
	- Added support for rich push (image inside a notification). Nothing to implement, everything is managed internally by the SDK
	- Added the possibility to set the color of a notification icon (method setNotificationIconColor on SMManager)
	- Added an overload to SMUserLogin, SMUserLogout, SMUserRegister, SMUserUnregister constructors that doesn’t require the email.
	- Added overloads to the Observe methods of SMObserverManager to give the possibility to change the behaviour regarding when the onChanged events are triggered on the observers. 
- Version 3.1.0
	- FirebaseJobDispatcher, which was deprecated by Google and will not be supported anymore starting April 2020, was replaced by WorkManager. The only impact is the change in dependencies in the Gradle file (cf. Other libraries)
	- The Engage SDK was tested with the latest version of the PlotProject library (3.10.0 at the time of writing) which can be safely used.
- Version 3.0.0
	- Adapted the SDK to be compatible with Firebase-Messaging 19 (and above), and Google-play-services 17 (and above) by replacing the "support" libraries by the corresponding AndroidX ones. This means your app must use AndroidX to use this version of the SDK. It is not compatible anymore with the support libraries and, therefore with the Firebase-Messaging 18 and below, and Google-Play-Services 16 and below.
	- Deprecated all the broadcasts (they are still sent, though)
	- Added the management of observers to observe events. They replace the deprecated broadcasts.
	- Added Android 10 support (API 29).
	- To migrate to this version: if it is not already done, use Android Studio to migrate to AndroidX (Refactor -> Migrate to AndroidX) then replace your BroadcastReceiver that listened to our
broadcasts by different observers depending on what you want to listen to as describe in the documentation above.
	- - Version 2.3.0
	- Added Android 10 support (API 29).
	- This version of the SDK is NOT compatible with Firebase-Messaging 19 (and above) and Google-Play-Services 17 (and above)
	- This version was made compatible with Android 10 (API 29) but it still uses the support libraries which will not be updated to 29 as Google pushes to migrate to AndroidX. So, if you want to update your app to target API 29, we recommend migrating to AndroidX and use version 3.0.0 of our SDK.
- Version 2.2.0
	- Updated minSdk to 16 to ensure compatibility with Firebase-Messaging 18
	- Added another service to retrieve the token extending FirebaseMessagingService
	- Improved way to manage the token after retrieval
	- Moved the retrieval of the user agent to the background when possible (still done in main thread for old Android versions)
	- Fixed Activity leak
	- This version of the SDK is NOT compatible with Firebase-Messaging 19 and Google-Play-Services 17
- Version 2.1.2
	- Fixed a ConcurrentModificationException appearing sometimes.
	- Fixed a bug when event callbacks are called out of context.
	- Fixed a bug where calling displayLastReceivedRemotePushNotification displayed an encrypted message.
	- Reworked the Reload method.
	- Updated an error log to facilitate the resolution of the problem.
- Version 2.1.1
	- Fixed a bug preventing the retry of events when opening the app if the cache is loaded synchronously.
	- Fixed a bug sending twice the PushReceived event when the push is received while the app is closed and the cache is set to load asynchronously.
	- Fixed a bug in SMBaseActivity regarding when some operations are executed.
- Version 2.1.0
	- Added the setting LoadCacheAsynchronously to read the cache in a separate thread. All writing is now always done in a separate thread.
	- Added the setting DoNotFetchTheToken to prevent the SDK from fetching the Firebase token itself. If set to true, it then becomes the responsibility of the app to do it and give it to the SDK using SMManager.getInstance().setFirebaseToken(String token)
	- Added the setting DoNotListenToThePush to prevent the SDK from listening to the push itself. If set to true, it then becomes the responsibility of the app to do it and give it to the SDK using SMManager.getInstance().displayNotification(Context context, Intent intent)
- Version 2.0.2
	- Bug fix for Android versions <= KitKat (4.4)
- Version 2.0.1
	- Bug fix when sending the token to the platform
- Version 2.0.0
	- Added decryption of push messages
	- Added Android P (API 28) support
	- Added new way to retrieve FCM token (done automatically by the SDK, no extra call to our API needed)
	- Improved communication security
	- Deprecated the registration to FCM through the registerDevice method. Use the JSON file instead.
- Version 1.9
	- Added management of buttons inside the notification.
- Version 1.8
	- Added management of push without In-App messages and with an action triggered when clicking on the notification (like a deep link).
- Version 1.7.2
	- Corrected a bug preventing the push to be correctly handled when received while on a webview opened by a previous notification.
- Version 1.7.1
	- Corrected a bug preventing the image to be correctly displayed in an InApp-Content fragment when the image was larger than the screen.
- Version 1.7.0
	- Added geolocation functionality
	- Android 8.1 compatible
- Version 1.6.1
	- Bug correction
- Version 1.6.0
	- Adaptations for Android O.
	- Removal of the service com.selligent.sdk.GcmIntentService. If you reference it in your AndroidManifest.xml file, remove that entry.
	- The broadcast BROADCAST_EVENT_RECEIVED_REMOTE_NOTIFICATION is now deprecated due to limitations with Android O. It is still sent but will not be received by an app targeting Android O and running on an Android O device.
- Version 1.5.0
	- Image type In App contents can now be marked at creation as downloadable. In that case, after retrieving the In App contents, the SDK will (asynchronously) download the image for each content marked as such and store it on the device.
	- Due to changes in the Android SDK, the inclusion of the third party library com.drewnoakes:metadata-extractor is now required when using "Response" type buttons within a push or In-App messages.
	- "Dangerous" permissions (those requiring to be explicitly granted by the user under Android 6.0 and above) are not included in the AndroidManifest.xml by the SDK anymore, it will have to be done in the app manifest. This will allow to restrict the permissions to the functionality actually used by the app. See each functionality to know which permission they require.
	- Added support for Android SDK 24 and 25.
	- Added management of "Passbook" type buttons with push, In-App message. Clicking on such a button will open a passbook app if the device has one or the browser instead.
- Version 1.4.3
	- sendSMEvent, when used with a custom event, will only send it if the data passed is new. If all entries in the hashtable have the same values as the last time it was sent, then we won’t do anything. If you want to log when a specific action happened and the values do not change, add a date in the data.
- Version 1.4.2
	- Engage SDK now available from JCenter
- Version 1.4
	- SMSettings.Theme is now deprecated. This value is not used anymore as the layout of the dialog in now completely customizable (cf. Dialog).
	- The design of a dialog does not try to adapt to the theme and the version of Android anymore, instead there is a default material layout that is entirely customizable (cf. Dialog).
	- The SetInfo event is now sent only when some of its info changed, not systematically at each start of the SDK anymore.
	- Added support for Android SDK 23 and the new way permissions are managed.
	- Added In-App contents management.
