//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[start](start.md)

# start

[androidJvm]\
open fun [start](start.md)(settings: [SMSettings](../-s-m-settings/index.md))

Mandatory method used to setup the Selligent Mobile SDK. It can only be called once (usually in an class extending SMApplication). Any later call with different values would be ineffective. Use this version ONLY if you extend [SMApplication](../-s-m-application/index.md)

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMSettings](../-s-m-settings/index.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| settings | an SMSettings object containing the Google application id, the web service URL, the Selligent client id and the Selligent private key. |

[androidJvm]\
open fun [start](start.md)(settings: [SMSettings](../-s-m-settings/index.md), application: [Application](https://developer.android.com/reference/kotlin/android/app/Application.html))

Mandatory method used to setup the Selligent Mobile SDK. It can only be called once (usually in an class extending SMApplication). Any later call with different values would be ineffective. You must use this version if you do not extend [SMApplication](../-s-m-application/index.md)

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMSettings](../-s-m-settings/index.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| settings | an SMSettings object containing the Google application id, the web service URL, the Selligent client id and the Selligent private key. |
| application | the instance of the class extending Application |
