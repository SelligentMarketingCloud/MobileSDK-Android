//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)/[InAppMessageRefreshType](-in-app-message-refresh-type.md)

# InAppMessageRefreshType

[androidJvm]\
open var [InAppMessageRefreshType](-in-app-message-refresh-type.md): [SMInAppRefreshType](../-s-m-in-app-refresh-type/index.md)

This is will tell how often the SDK must get the In App messages. Setting this property WILL enable the In App messages in the SDK, even if the value is set to &quot;None&quot;. If you do not want to enable the In App messages, leave it to null. If you do not set a value, you can still do it later by calling [enableInAppMessages](../-s-m-manager/enable-in-app-messages.md)
