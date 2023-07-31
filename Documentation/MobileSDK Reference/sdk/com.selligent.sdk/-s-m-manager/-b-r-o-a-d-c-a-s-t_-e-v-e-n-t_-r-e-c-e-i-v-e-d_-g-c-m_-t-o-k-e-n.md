//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_EVENT_RECEIVED_GCM_TOKEN](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md)

# BROADCAST_EVENT_RECEIVED_GCM_TOKEN

[androidJvm]\
val [~~BROADCAST_EVENT_RECEIVED_GCM_TOKEN~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-g-c-m_-t-o-k-e-n.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) = &quot;SMReceivedGCMToken&quot;

---

### Deprecated (for removal)

Since version 3.0.0

---

String representing a broadcast name you can listen to. It is broadcasted after receiving the GCM token and only if it changed. Primary-application may use this broadcast to retrieve the GCM token. This broadcast is sent locally using [sendBroadcast](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast)

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeToken](../-s-m-observer-manager/observe-token.md) instead.

#### See also

| |
|---|
| [LocalBroadcastManager](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast) |
