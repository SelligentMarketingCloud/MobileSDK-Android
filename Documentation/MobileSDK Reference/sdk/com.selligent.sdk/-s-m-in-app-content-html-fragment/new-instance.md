//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMInAppContentHtmlFragment](index.md)/[newInstance](new-instance.md)

# newInstance

[androidJvm]\
open fun [newInstance](new-instance.md)(category: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [SMInAppContentHtmlFragment](index.md)

Method used to create a new instance of SMInAppContentHtmlFragment that will display all the HTML In App Contents available

#### Return

the new instance of SMInAppContentImageFragment or null if one of the parameters is null.

## Parameters

androidJvm

| | |
|---|---|
| category | String specifying the category of the content |

[androidJvm]\
open fun [newInstance](new-instance.md)(category: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [SMInAppContentHtmlFragment](index.md)

Method used to create a new instance of SMInAppContentHtmlFragment

#### Return

the new instance of SMInAppContentImageFragment or null if one of the parameters is null.

## Parameters

androidJvm

| | |
|---|---|
| category | String specifying the category of the content |
| count | number of In App contents to display. A value of -1 will display all contents available. Values 0 and inferior to -1 are invalid. |
