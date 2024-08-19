//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_DATA_IN_APP_MESSAGES](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-m-e-s-s-a-g-e-s.md)

# BROADCAST_DATA_IN_APP_MESSAGES

[androidJvm]\
val [~~BROADCAST_DATA_IN_APP_MESSAGES~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-m-e-s-s-a-g-e-s.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) = &quot;SMDataInAppMessages&quot;

---

### Deprecated (for removal)

Since version 3.0.0

---

String representing a key to retrieve an object inside an intent Use this key to retrieve an array of [SMInAppMessage](../-s-m-in-app-message/index.md) from the intent received from the broadcast [BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md). This broadcast is sent locally using sendBroadcast

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeInAppMessages](../-s-m-observer-manager/observe-in-app-messages.md) instead.

#### See also

| |
|---|
| LocalBroadcastManager |
| [SMInAppMessage](../-s-m-in-app-message/index.md) |
| [BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md) |
