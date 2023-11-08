//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[setFirebaseToken](set-firebase-token.md)

# setFirebaseToken

[androidJvm]\
open fun [setFirebaseToken](set-firebase-token.md)(token: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))

This method is to be used only if you set [DoNotFetchTheToken](../-s-m-settings/-do-not-fetch-the-token.md) to true. It will store the token in the SDK cache and send it to the Marigold Engage platform if needed (if the SDK doesn't have it already or if the token changed)

#### Parameters

androidJvm

| | |
|---|---|
| token | The string that you got from Firebase to enable push notifications. |
