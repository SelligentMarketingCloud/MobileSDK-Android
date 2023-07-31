//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMNotificationButton](index.md)/[getAction](get-action.md)

# getAction

[androidJvm]\
open fun [~~getAction~~](get-action.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

---

### Deprecated

---

The action that will be executed when clicking on the button. Possible values are: 0 - default (does nothing, if in a dialog, closes it) 1 - Phone 2 - SMS 3 - E-Mail 4 - Url 5 - Open app 6 - Open store 7 - Event 11 - Passbook 12 - Journey map 13 - Deep link

#### Return

the int representing the type of the button

#### Deprecated

since 4.0, use [getLinkAction](get-link-action.md) instead
