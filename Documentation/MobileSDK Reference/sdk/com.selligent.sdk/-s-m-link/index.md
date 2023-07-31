//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMLink](index.md)

# SMLink

[androidJvm]\
open class [SMLink](index.md) : [SMNotificationButton](../-s-m-notification-button/index.md)

A link of an [SMInAppContent](../-s-m-in-app-content/index.md).

## Constructors

| | |
|---|---|
| [SMLink](-s-m-link.md) | [androidJvm]<br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [action](../-s-m-notification-button/action.md) | [androidJvm]<br>open var [action](../-s-m-notification-button/action.md): [SMLinkAction](../-s-m-link-action/index.md) |
| [data](../-s-m-notification-button/data.md) | [androidJvm]<br>open var [data](../-s-m-notification-button/data.md): [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt; |
| [id](../-s-m-notification-button/id.md) | [androidJvm]<br>open var [id](../-s-m-notification-button/id.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [label](../-s-m-notification-button/label.md) | [androidJvm]<br>open var [label](../-s-m-notification-button/label.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [type](../-s-m-notification-button/type.md) | [androidJvm]<br>open var [type](../-s-m-notification-button/type.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [value](../-s-m-notification-button/value.md) | [androidJvm]<br>open var [value](../-s-m-notification-button/value.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Functions

| Name | Summary |
|---|---|
| [getAction](../-s-m-notification-button/get-action.md) | [androidJvm]<br>open fun [~~getAction~~](../-s-m-notification-button/get-action.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The action that will be executed when clicking on the button. |
| [getId](../-s-m-notification-button/get-id.md) | [androidJvm]<br>open fun [getId](../-s-m-notification-button/get-id.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [getLabel](../-s-m-notification-button/get-label.md) | [androidJvm]<br>open fun [getLabel](../-s-m-notification-button/get-label.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [getLinkAction](../-s-m-notification-button/get-link-action.md) | [androidJvm]<br>open fun [getLinkAction](../-s-m-notification-button/get-link-action.md)(): [SMLinkAction](../-s-m-link-action/index.md) |
| [getValue](../-s-m-notification-button/get-value.md) | [androidJvm]<br>open fun [getValue](../-s-m-notification-button/get-value.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [readExternal](../-s-m-notification-button/read-external.md) | [androidJvm]<br>open fun [readExternal](../-s-m-notification-button/read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object.<br>[androidJvm]<br>abstract fun [readExternal](../-s-m-notification-message/index.md#-1306664077%2FFunctions%2F462465411)(p: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html)) |
| [writeExternal](../-s-m-notification-button/write-external.md) | [androidJvm]<br>open fun [writeExternal](../-s-m-notification-button/write-external.md)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object.<br>[androidJvm]<br>abstract fun [writeExternal](../-s-m-notification-message/index.md#1500408595%2FFunctions%2F462465411)(p: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html)) |
