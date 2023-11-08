//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[start](start.md)

# start

[androidJvm]\
open fun [start](start.md)(settings: [SMSettings](../-s-m-settings/index.md))

Mandatory method used to setup the Marigold Engage Mobile SDK. It can only be called once (usually in an class extending SMApplication). Any later call with different values would be ineffective. Use this version ONLY if you extend [SMApplication](../-s-m-application/index.md)

#### Parameters

androidJvm

| | |
|---|---|
| settings | an SMSettings object containing the Google application id, the web service URL, the Marigold Engage client id and the Marigold Engage private key. |

#### See also

| |
|---|
| [SMSettings](../-s-m-settings/index.md) |

[androidJvm]\
open fun [start](start.md)(settings: [SMSettings](../-s-m-settings/index.md), application: [Application](https://developer.android.com/reference/kotlin/android/app/Application.html))

Mandatory method used to setup the Marigold Engage Mobile SDK. It can only be called once (usually in an class extending SMApplication). Any later call with different values would be ineffective. You must use this version if you do not extend [SMApplication](../-s-m-application/index.md)

#### Parameters

androidJvm

| | |
|---|---|
| settings | an SMSettings object containing the Google application id, the web service URL, the Marigold Engage client id and the Marigold Engage private key. |
| application | the instance of the class extending Application |

#### See also

| |
|---|
| [SMSettings](../-s-m-settings/index.md) |
