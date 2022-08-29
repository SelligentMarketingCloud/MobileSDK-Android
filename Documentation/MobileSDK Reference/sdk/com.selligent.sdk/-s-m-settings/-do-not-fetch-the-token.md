//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)/[DoNotFetchTheToken](-do-not-fetch-the-token.md)

# DoNotFetchTheToken

[androidJvm]\
open var [DoNotFetchTheToken](-do-not-fetch-the-token.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

If set to true, the SDK will not try to retrieve the token used for push notification from Firebase. Instead, you will be responsible to retrieve it and give it to the SDK by calling the method [setFirebaseToken](../-s-m-manager/set-firebase-token.md) every time the token changes. Use this if you already have your own way to retrieve the token and do not need the SDK to do it. Default value is false.
