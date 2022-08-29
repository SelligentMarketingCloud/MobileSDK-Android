//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[getInAppContents](get-in-app-contents.md)

# getInAppContents

[androidJvm]\
open fun [getInAppContents](get-in-app-contents.md)(category: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), type: [SMContentType](../-s-m-content-type/index.md), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[SMInAppContent](../-s-m-in-app-content/index.md)&gt;

Gets the list of valid [SMInAppContent](../-s-m-in-app-content/index.md) for the given type and category. Use this method if you do not want to implement our Fragments.

#### Return

An [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html) of [SMInAppContent](../-s-m-in-app-content/index.md).

## Parameters

androidJvm

| | |
|---|---|
| category | The category of the [SMInAppContent](../-s-m-in-app-content/index.md). |
| type | The [SMContentType](../-s-m-content-type/index.md) of the SMInAppContent. |
| max | The number of contents to get. -1 to get them all. |

[androidJvm]\
open fun [getInAppContents](get-in-app-contents.md)(category: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), type: [SMContentType](../-s-m-content-type/index.md), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), callbackEvent: [SMInAppContentReturn](../-s-m-in-app-content-return/index.md))

Gets the list of valid [SMInAppContent](../-s-m-in-app-content/index.md) for the given type and category. Use this method if you do not want to implement our Fragments.

## Parameters

androidJvm

| | |
|---|---|
| category | The category of the [SMInAppContent](../-s-m-in-app-content/index.md). |
| type | The [SMContentType](../-s-m-content-type/index.md) of the SMInAppContent. |
| max | The number of contents to get. -1 to get them all. |
| callbackEvent | The event that will be called when the contents are retrieved. It will be passed an [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html) of [SMInAppContent](../-s-m-in-app-content/index.md) |
