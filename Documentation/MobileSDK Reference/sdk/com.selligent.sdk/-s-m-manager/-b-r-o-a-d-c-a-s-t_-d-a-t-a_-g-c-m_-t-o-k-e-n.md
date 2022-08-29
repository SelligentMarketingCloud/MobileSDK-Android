//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_DATA_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-g-c-m_-t-o-k-e-n.md)

# BROADCAST_DATA_GCM_TOKEN

[androidJvm]\

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~val~~ [~~BROADCAST_DATA_GCM_TOKEN~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-g-c-m_-t-o-k-e-n.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)

String representing a key to retrieve an object inside an intent Use this key to retrieve the GCM token from the intent received from the broadcast [BROADCAST_EVENT_RECEIVED_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md). This broadcast is sent locally using [sendBroadcast](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast)

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeToken](../-s-m-observer-manager/observe-token.md) instead.

## See also

androidJvm

| | |
|---|---|
| [androidx.localbroadcastmanager.content.LocalBroadcastManager](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast) |  |
| [BROADCAST_EVENT_RECEIVED_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md) |  |
