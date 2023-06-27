//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMInAppContent](index.md)

# SMInAppContent

[androidJvm]\
open class [SMInAppContent](index.md) : BaseMessage, [Externalizable](https://developer.android.com/reference/kotlin/java/io/Externalizable.html)

An In App content

## Constructors

| | |
|---|---|
| [SMInAppContent](-s-m-in-app-content.md) | [androidJvm]<br>open fun [SMInAppContent](-s-m-in-app-content.md)()<br>Empty constructor of an In App Content |
| [SMInAppContent](-s-m-in-app-content.md) | [androidJvm]<br>open fun [SMInAppContent](-s-m-in-app-content.md)(jSon: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Constructor that fills in the In App Content based on the given json |

## Types

| Name | Summary |
|---|---|
| [DisplayMode](-display-mode/index.md) | [androidJvm]<br>enum [DisplayMode](-display-mode/index.md)<br>Enum listing the different display mode. |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [androidJvm]<br>open fun [equals](equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares this instance with the specified object and indicates if they are equal. |
| [getBody](get-body.md) | [androidJvm]<br>open fun [getBody](get-body.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the body of the SMInAppContent |
| [getCreationDate](get-creation-date.md) | [androidJvm]<br>open fun [getCreationDate](get-creation-date.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the creation date of the SMInAppContent |
| [getExpirationDate](get-expiration-date.md) | [androidJvm]<br>open fun [getExpirationDate](get-expiration-date.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Gets the expiration date of the SMInAppContent |
| [getId](get-id.md) | [androidJvm]<br>open fun [getId](get-id.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the id of the SMInAppContent |
| [getTitle](get-title.md) | [androidJvm]<br>open fun [getTitle](get-title.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Gets the title of the SMInAppContent |
| [hasBeenFirstSeenInCurrentSession](has-been-first-seen-in-current-session.md) | [androidJvm]<br>open fun [hasBeenFirstSeenInCurrentSession](has-been-first-seen-in-current-session.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tells if the SMInAppContent has already been seen or not in the current session. |
| [hasBeenSeen](has-been-seen.md) | [androidJvm]<br>open fun [hasBeenSeen](has-been-seen.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tells if the SMInAppContent has already been seen or not. |
| [hashCode](hash-code.md) | [androidJvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns an integer hash code for this object. |
| [readExternal](read-external.md) | [androidJvm]<br>open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))<br>This method is called when deserializing the object. |
| [writeExternal](write-external.md) | [androidJvm]<br>open fun [writeExternal](write-external.md)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html))<br>This method is called when serializing the object. |

## Properties

| Name | Summary |
|---|---|
| [category](category.md) | [androidJvm]<br>open val [category](category.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [displayMode](display-mode.md) | [androidJvm]<br>open val [displayMode](display-mode.md): [SMInAppContent.DisplayMode](-display-mode/index.md) |
| [image](image.md) | [androidJvm]<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open val [image](image.md): [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html) |
| [links](links.md) | [androidJvm]<br>open val [links](links.md): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMLink](../-s-m-link/index.md)&gt; |
| [type](type.md) | [androidJvm]<br>open val [type](type.md): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
