//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md)

# BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE

[androidJvm]\
val [~~BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) = &quot;SMReceivedInAppMessage&quot;

---

### Deprecated (for removal)

Since version 3.0.0

---

String representing a broadcast name you can listen to. It is broadcasted shortly after receiving InApp messages Primary-application may use this notification to manage the received InApp messages This broadcast is sent locally using sendBroadcast

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeInAppMessages](../-s-m-observer-manager/observe-in-app-messages.md) instead.

#### See also

| |
|---|
| LocalBroadcastManager |
