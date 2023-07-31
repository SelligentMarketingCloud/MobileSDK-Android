//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_EVENT_BUTTON_CLICKED](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md)

# BROADCAST_EVENT_BUTTON_CLICKED

[androidJvm]\
val [~~BROADCAST_EVENT_BUTTON_CLICKED~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-b-u-t-t-o-n_-c-l-i-c-k-e-d.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) = &quot;SMEventButtonClicked&quot;

---

### Deprecated (for removal)

Since version 3.0.0

---

String representing a broadcast name you can listen to. It is broadcasted when the user interacts with a remote-notification Usefull to retrieve user's actions on a received remote-notification. This broadcast is sent locally using [sendBroadcast](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast)

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeClickedButton](../-s-m-observer-manager/observe-clicked-button.md) instead.

#### See also

| |
|---|
| [LocalBroadcastManager](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast) |
