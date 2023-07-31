//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)

# SMSettings

open class [SMSettings](index.md)

Configuration object passed to the 'start' method of SMManager.

#### See also

| |
|---|
| [SMManager](../-s-m-manager/start.md) |

## Constructors

| | |
|---|---|
| [SMSettings](-s-m-settings.md) | [androidJvm]<br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [AddInAppMessageFromPushToInAppMessageList](-add-in-app-message-from-push-to-in-app-message-list.md) | [androidJvm]<br>open var [AddInAppMessageFromPushToInAppMessageList](-add-in-app-message-from-push-to-in-app-message-list.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>If set to true, any In-App Message received through a push notification will be added to the list of In-App Messages retrieved by the SDK and will be available via [getInAppMessages](../-s-m-manager/get-in-app-messages.md). |
| [ClearCacheIntervalValue](-clear-cache-interval-value.md) | [androidJvm]<br>open var [ClearCacheIntervalValue](-clear-cache-interval-value.md): [SMClearCache](../-s-m-clear-cache/index.md)<br>This value tells how often the SDK's inAppMessagesCache mechanism should clear itself. |
| [ClientId](-client-id.md) | [androidJvm]<br>open var [ClientId](-client-id.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>The client id given by Selligent to contact the web services |
| [ConfigureGeolocation](-configure-geolocation.md) | [androidJvm]<br>open var [~~ConfigureGeolocation~~](-configure-geolocation.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This will tell the SDK to use the geolocation. |
| [DoNotFetchTheToken](-do-not-fetch-the-token.md) | [androidJvm]<br>open var [DoNotFetchTheToken](-do-not-fetch-the-token.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>If set to true, the SDK will not try to retrieve the token used for push notification from Firebase. |
| [DoNotListenToThePush](-do-not-listen-to-the-push.md) | [androidJvm]<br>open var [DoNotListenToThePush](-do-not-listen-to-the-push.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>If set to true, the SDK will not listen for the push anymore. |
| [EnableNotifications](-enable-notifications.md) | [androidJvm]<br>open var [EnableNotifications](-enable-notifications.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>If set to true, the notifications will be enabled as soon as the token is retrieved (this is the default behaviour). |
| [FrameworkType](-framework-type.md) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open var [FrameworkType](-framework-type.md): [SMFrameworkType](../-s-m-framework-type/index.md)<br>This property is only intended to be used by the plugins wrapping our SDK. |
| [InAppContentRefreshType](-in-app-content-refresh-type.md) | [androidJvm]<br>open var [InAppContentRefreshType](-in-app-content-refresh-type.md): [SMInAppRefreshType](../-s-m-in-app-refresh-type/index.md)<br>This is will tell how often the SDK must get the In App content. |
| [InAppMessageRefreshType](-in-app-message-refresh-type.md) | [androidJvm]<br>open var [InAppMessageRefreshType](-in-app-message-refresh-type.md): [SMInAppRefreshType](../-s-m-in-app-refresh-type/index.md)<br>This is will tell how often the SDK must get the In App messages. |
| [LoadCacheAsynchronously](-load-cache-asynchronously.md) | [androidJvm]<br>open var [LoadCacheAsynchronously](-load-cache-asynchronously.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>This will make the SDK load the content of its cache asynchronously. |
| [NotificationChannelDescription](-notification-channel-description.md) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open var [NotificationChannelDescription](-notification-channel-description.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Override this value to set a description of the channel It is visible in the notification channel setting screen of the device. |
| [NotificationChannelId](-notification-channel-id.md) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open var [NotificationChannelId](-notification-channel-id.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Override this value if you already have a channel setup in your app and you want the SDK to use it. |
| [NotificationChannelName](-notification-channel-name.md) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open var [NotificationChannelName](-notification-channel-name.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Override this value to set the name of the channel. |
| [PrivateKey](-private-key.md) | [androidJvm]<br>open var [PrivateKey](-private-key.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>The private key given by Selligent to contact the legacy services. |
| [RemoteMessageDisplayType](-remote-message-display-type.md) | [androidJvm]<br>open var [RemoteMessageDisplayType](-remote-message-display-type.md): [SMRemoteMessageDisplayType](../-s-m-remote-message-display-type/index.md)<br>If set to Automatic, when the app is active, the remote push messages will automatically be displayed. |
| [WebServiceUrl](-web-service-url.md) | [androidJvm]<br>open var [WebServiceUrl](-web-service-url.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>The URL of the Selligent web services |
| [WebViewNavigationOverride](-web-view-navigation-override.md) | [androidJvm]<br>open var [WebViewNavigationOverride](-web-view-navigation-override.md): [SMWebViewNavigationOverride](../-s-m-web-view-navigation-override/index.md)<br>Instantiate this if you want to override the navigation in the WebViews displayed by the In-App messages. |
