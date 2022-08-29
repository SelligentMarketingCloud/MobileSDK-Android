//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_DATA_BUTTON](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-b-u-t-t-o-n.md)

# BROADCAST_DATA_BUTTON

[androidJvm]\

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~val~~ [~~BROADCAST_DATA_BUTTON~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-b-u-t-t-o-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)

String representing a key to retrieve an object inside an intent Use this key to retrive the object [SMNotificationButton](../-s-m-notification-button/index.md) from the intent received from the broadcast [BROADCAST_EVENT_BUTTON_CLICKED](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md). This broadcast is sent locally using [sendBroadcast](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast)

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeClickedButton](../-s-m-observer-manager/observe-clicked-button.md) instead.

## See also

androidJvm

| | |
|---|---|
| [androidx.localbroadcastmanager.content.LocalBroadcastManager](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast) |  |
| [com.selligent.sdk.SMNotificationButton](../-s-m-notification-button/index.md) |  |
| [BROADCAST_EVENT_BUTTON_CLICKED](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md) |  |
