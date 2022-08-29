//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMInAppMessage](index.md)/[readExternal](read-external.md)

# readExternal

[androidJvm]\
open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))

This method is called when deserializing the object. It should not be called manually.

## Parameters

androidJvm

| | |
|---|---|
| serializedObject | the [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html) object containing all the values of the SMInAppMessage object to recreate. |

## Throws

| | |
|---|---|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) |  |
| [java.lang.ClassNotFoundException](https://developer.android.com/reference/kotlin/java/lang/ClassNotFoundException.html) |  |
