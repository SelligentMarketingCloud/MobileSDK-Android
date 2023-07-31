//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEvent](index.md)/[readExternal](read-external.md)

# readExternal

[androidJvm]\
open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html))

This method is called when deserializing the object. It should not be called manually.

#### Parameters

androidJvm

| | |
|---|---|
| serializedObject | the [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html) object containing all the values of the SMEvent object to recreate. |

#### Throws

| |
|---|
| [IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) |
| [ClassNotFoundException](https://developer.android.com/reference/kotlin/java/lang/ClassNotFoundException.html) |
