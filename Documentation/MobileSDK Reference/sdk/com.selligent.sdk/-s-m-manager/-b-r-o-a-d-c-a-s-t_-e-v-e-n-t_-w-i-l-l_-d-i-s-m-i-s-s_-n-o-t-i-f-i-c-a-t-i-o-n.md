//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-m-i-s-s_-n-o-t-i-f-i-c-a-t-i-o-n.md)

# BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION

[androidJvm]\
val [~~BROADCAST_EVENT_WILL_DISMISS_NOTIFICATION~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-m-i-s-s_-n-o-t-i-f-i-c-a-t-i-o-n.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) = &quot;SMEventWillDismissNotification&quot;

---

### Deprecated (for removal)

Since version 3.0.0

---

String representing a broadcast name you can listen to. It is broadcasted shortly before dismissing the current remote-notification Primary-application may use this broadcast to resume any paused work. (see [BROADCAST_EVENT_WILL_DISPLAY_NOTIFICATION](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-p-l-a-y_-n-o-t-i-f-i-c-a-t-i-o-n.md)) This broadcast is sent locally using [sendBroadcast](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast)

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeDismissedMessage](../-s-m-observer-manager/observe-dismissed-message.md) instead.

#### See also

| |
|---|
| [LocalBroadcastManager](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast) |
| [BROADCAST_EVENT_WILL_DISPLAY_NOTIFICATION](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-w-i-l-l_-d-i-s-p-l-a-y_-n-o-t-i-f-i-c-a-t-i-o-n.md) |
