//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[sendSMEvent](send-s-m-event.md)

# sendSMEvent

[androidJvm]\
open fun [sendSMEvent](send-s-m-event.md)(event: [SMEvent](../-s-m-event/index.md))

Use this method to send an event to the Marigold Engage platform. If you are sending a simple [SMEvent](../-s-m-event/index.md), then we will check if the values are different from the last time you sent them. If they are not, the event won't be sent.

#### Parameters

androidJvm

| | |
|---|---|
| event | an SMEvent object |

#### See also

| |
|---|
| [SMEvent](../-s-m-event/index.md) |
| [SMEventUserLogin](../-s-m-event-user-login/index.md) |
| [SMEventUserLogout](../-s-m-event-user-logout/index.md) |
| [SMEventUserRegister](../-s-m-event-user-register/index.md) |
| [SMEventUserUnregister](../-s-m-event-user-unregister/index.md) |
