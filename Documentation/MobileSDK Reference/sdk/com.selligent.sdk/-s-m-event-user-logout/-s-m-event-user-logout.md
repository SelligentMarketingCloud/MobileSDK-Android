//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMEventUserLogout](index.md)/[SMEventUserLogout](-s-m-event-user-logout.md)

# SMEventUserLogout

[androidJvm]\
constructor()

[androidJvm]\
constructor(profileId: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))

Constructs a new SMEventUserLogout

#### Parameters

androidJvm

| | |
|---|---|
| profileId | a String containing the profile id of the user (depending on your app, it can be an e-mail address, a user ID, etc.). |
| data | a Hashtable<String, String> containing custom data, can be null. |
| callback | an SMCallback containing code to perform after the message is sent |

#### See also

| |
|---|
| [SMCallback](../-s-m-callback/index.md) |

[androidJvm]\
constructor(data: [Hashtable](https://developer.android.com/reference/kotlin/java/util/Hashtable.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;, callback: [SMCallback](../-s-m-callback/index.md))

Constructs a new SMEventUserLogout

#### Parameters

androidJvm

| | |
|---|---|
| data | a Hashtable<String, String> containing custom data, can be null. |
| callback | an SMCallback containing code to perform after the message is sent |

#### See also

| |
|---|
| [SMCallback](../-s-m-callback/index.md) |
