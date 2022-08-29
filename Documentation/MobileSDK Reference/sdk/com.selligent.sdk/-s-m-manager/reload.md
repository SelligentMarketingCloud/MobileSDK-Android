//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[reload](reload.md)

# reload

[androidJvm]\
open fun [reload](reload.md)(settings: [SMSettings](../-s-m-settings/index.md), callback: [SMCallback](../-s-m-callback/index.md))

This method is used in the special case of the Selligent demo app Parana and should not be needed. It allows to change the settings given at startup by the start method.

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
| callback | an SMCallback object to execute code after the reload is finished and the device id for the new environment is retrieved |
