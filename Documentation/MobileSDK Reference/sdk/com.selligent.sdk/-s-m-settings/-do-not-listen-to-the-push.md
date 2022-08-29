//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)/[DoNotListenToThePush](-do-not-listen-to-the-push.md)

# DoNotListenToThePush

[androidJvm]\
open var [DoNotListenToThePush](-do-not-listen-to-the-push.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

If set to true, the SDK will not listen for the push anymore. Instead, you will be responsible to listen and give it to the SDK by calling the method [displayNotification](../-s-m-manager/display-notification.md) every time a push is received. Use this if you already have your own way to listent to the Firebase push and do not want the SDK to do it. Default value is false
