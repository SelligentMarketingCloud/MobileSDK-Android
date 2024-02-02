//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEvent](index.md)/[SMEvent](-s-m-event.md)

# SMEvent

[androidJvm]\
constructor()

Constructs an SMEvent object without data and callback

[androidJvm]\
constructor(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))

Constructs an SMEvent object with the following:

#### Parameters

androidJvm

| | |
|---|---|
| name | the name of the event |
| data | a Hashtable<String, String> containing the custom data |
| callback | a SMCallback object containing code to execute after the message is sent |

#### See also

| |
|---|
| [SMCallback](../-s-m-callback/index.md) |

[androidJvm]\
constructor(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), @NotNullprofileId: @NotNull[String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))

Constructs an SMEvent object with the following:

#### Parameters

androidJvm

| | |
|---|---|
| name | the name of the event |
| profileId | a String containing the profile id of the user (depending on your app, it can be an e-mail address, a user ID, etc.). |
| data | a Hashtable<String, String> containing the custom data |
| callback | a SMCallback object containing code to execute after the message is sent |

#### See also

| |
|---|
| [SMCallback](../-s-m-callback/index.md) |

[androidJvm]\
constructor(data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))

---

### Deprecated

---

Constructs an SMEvent object with the following:

#### Deprecated

since 4.0, use [SMEvent](-s-m-event.md) instead

#### Parameters

androidJvm

| | |
|---|---|
| data | a Hashtable<String, String> containing the custom data |
| callback | a SMCallback object containing code to execute after the message is sent |

#### See also

| |
|---|
| [SMCallback](../-s-m-callback/index.md) |
