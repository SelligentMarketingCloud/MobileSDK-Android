//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[BROADCAST_EVENT_RECEIVED_IN_APP_CONTENTS](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md)

# BROADCAST_EVENT_RECEIVED_IN_APP_CONTENTS

[androidJvm]\

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~val~~ [~~BROADCAST_EVENT_RECEIVED_IN_APP_CONTENTS~~](-b-r-o-a-d-c-a-s-t_-e-v-e-n-t_-r-e-c-e-i-v-e-d_-i-n_-a-p-p_-c-o-n-t-e-n-t-s.md)~~:~~ [String](https://developer.android.com/reference/kotlin/java/lang/String.html)

String representing a broadcast name you can listen to. It is broadcasted shortly after receiving InApp contents Primary-application may use this notification to manage the received InApp contents This broadcast is sent locally using [sendBroadcast](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast)

#### Deprecated

LocalBroadcastManager being deprecated in latest versions of the androidx library, our broadcasts have been deprecated. Use [observeInAppContents](../-s-m-observer-manager/observe-in-app-contents.md) instead.

## See also

androidJvm

| | |
|---|---|
| [androidx.localbroadcastmanager.content.LocalBroadcastManager](https://developer.android.com/reference/kotlin/androidx/localbroadcastmanager/content/LocalBroadcastManager.html#sendbroadcast) |  |
