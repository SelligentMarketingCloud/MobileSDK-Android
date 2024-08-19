//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_DATA_IN_APP_CONTENTS](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md)

# BROADCAST_DATA_IN_APP_CONTENTS

[androidJvm]\
val [~~BROADCAST_DATA_IN_APP_CONTENTS~~](-b-r-o-a-d-c-a-s-t_-d-a-t-a_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) = &quot;SMDataInAppContents&quot;

---

### Deprecated (for removal)

Since version 3.0.0

---

String representing a key to retrieve an object inside an intent Use this key to retrieve an dictionary containing the number of contents for each category from the broadcast [BROADCAST_EVENT_RECEIVED_IN_APP_MESSAGE](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-m-e-s-s-a-g-e.md). This broadcast is sent locally using sendBroadcast

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeInAppContents](../-s-m-observer-manager/observe-in-app-contents.md) instead.

#### See also

| |
|---|
| LocalBroadcastManager |
| [BROADCAST_EVENT_RECEIVED_IN_APP_CONTENTS](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md) |
