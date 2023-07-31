//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMMapMarker](index.md)

# SMMapMarker

[androidJvm]\
open class [SMMapMarker](index.md) : [Externalizable](https://developer.android.com/reference/kotlin/java/io/Externalizable.html)

This class represents a point on a map.

## Constructors

| | |
|---|---|
| [SMMapMarker](-s-m-map-marker.md) | [androidJvm]<br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [description](description.md) | [androidJvm]<br>@SerializedName(value = &quot;desc&quot;)<br>open val [description](description.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [latitude](latitude.md) | [androidJvm]<br>@SerializedName(value = &quot;lat&quot;)<br>open val [latitude](latitude.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [longitude](longitude.md) | [androidJvm]<br>@SerializedName(value = &quot;lng&quot;)<br>open val [longitude](longitude.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [title](title.md) | [androidJvm]<br>open val [title](title.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Functions

| Name | Summary |
|---|---|
| [readExternal](read-external.md) | [androidJvm]<br>open fun [readExternal](read-external.md)(serializedObject: [ObjectInput](https://developer.android.com/reference/kotlin/java/io/ObjectInput.html)) |
| [writeExternal](write-external.md) | [androidJvm]<br>open fun [writeExternal](write-external.md)(serializedObject: [ObjectOutput](https://developer.android.com/reference/kotlin/java/io/ObjectOutput.html)) |
