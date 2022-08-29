//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[sendSMEvent](send-s-m-event.md)

# sendSMEvent

[androidJvm]\
open fun [sendSMEvent](send-s-m-event.md)(event: [SMEvent](../-s-m-event/index.md))

Use this method to send an event to the Selligent platform. If you are sending a simple [SMEvent](../-s-m-event/index.md), then we will check if the values are different from the last time you sent them. If they are not, the event won't be sent.

## See also

androidJvm

| | |
|---|---|
| [com.selligent.sdk.SMEvent](../-s-m-event/index.md) |  |
| [com.selligent.sdk.SMEventUserLogin](../-s-m-event-user-login/index.md) |  |
| [com.selligent.sdk.SMEventUserLogout](../-s-m-event-user-logout/index.md) |  |
| [com.selligent.sdk.SMEventUserRegister](../-s-m-event-user-register/index.md) |  |
| [com.selligent.sdk.SMEventUserUnregister](../-s-m-event-user-unregister/index.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| event | an SMEvent object |
