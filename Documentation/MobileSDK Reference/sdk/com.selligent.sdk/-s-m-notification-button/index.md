//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMNotificationButton](index.md)

# SMNotificationButton

[androidJvm]\
open class [SMNotificationButton](index.md) : [Externalizable](https://developer.android.com/reference/kotlin/java/io/Externalizable.html)

Object containing all the data used to implement a button in a notification/message.

## Constructors

| | |
|---|---|
| [SMNotificationButton](-s-m-notification-button.md) | [androidJvm]<br>open fun [SMNotificationButton](-s-m-notification-button.md)() |

## Functions

| Name | Summary |
|---|---|
| [getAction](get-action.md) | [androidJvm]<br>@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~open~~ ~~fun~~ [~~getAction~~](get-action.md)~~(~~~~)~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The action that will be executed when clicking on the button. |
| [getId](get-id.md) | [androidJvm]<br>open fun [getId](get-id.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [getLabel](get-label.md) | [androidJvm]<br>open fun [getLabel](get-label.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [getLinkAction](get-link-action.md) | [androidJvm]<br>open fun [getLinkAction](get-link-action.md)(): [SMLinkAction](../-s-m-link-action/index.md) |
| [getValue](get-value.md) | [androidJvm]<br>open fun [getValue](get-value.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [readExternal](read-external.md) | [androidJvm]<br>open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object. |
| [writeExternal](write-external.md) | [androidJvm]<br>open fun [writeExternal](write-external.md)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object. |

## Properties

| Name | Summary |
|---|---|
| [action](action.md) | [androidJvm]<br>open var [action](action.md): [SMLinkAction](../-s-m-link-action/index.md) |
| [data](data.md) | [androidJvm]<br>open var [data](data.md): [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt; |
| [id](id.md) | [androidJvm]<br>open var [id](id.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [label](label.md) | [androidJvm]<br>open var [label](label.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [type](type.md) | [androidJvm]<br>open var [type](type.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [value](value.md) | [androidJvm]<br>open var [value](value.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [SMLink](../-s-m-link/index.md) |
