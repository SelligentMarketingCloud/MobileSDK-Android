//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[getGCMToken](get-g-c-m-token.md)

# getGCMToken

[androidJvm]\
open fun [getGCMToken](get-g-c-m-token.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)

This methods returns the GCM token stored by the SDK. As the registration is asynchronous, the token returned may be empty or not up-to-date if the registration process is not completed.

#### Return

the stored GCM token
