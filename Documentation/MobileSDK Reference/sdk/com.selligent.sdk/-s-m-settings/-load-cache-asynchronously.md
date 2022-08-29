//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)/[LoadCacheAsynchronously](-load-cache-asynchronously.md)

# LoadCacheAsynchronously

[androidJvm]\
open var [LoadCacheAsynchronously](-load-cache-asynchronously.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

This will make the SDK load the content of its cache asynchronously. It improves performance at startup as reading the files will be done in a separate thread. This has an impact on the management of In-App contents, so if you are already using them and want to set this to true, you might have to review your code (cf. document &quot;Using the SDK&quot; for more information about this). If you don't already use the In-App contents, feel free to set this to true. Default value is false.
