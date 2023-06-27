//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)/[ClearCacheIntervalValue](-clear-cache-interval-value.md)

# ClearCacheIntervalValue

[androidJvm]\
open var [ClearCacheIntervalValue](-clear-cache-interval-value.md): [SMClearCache](../-s-m-clear-cache/index.md)

This value tells how often the SDK's inAppMessagesCache mechanism should clear itself. Internally, each notification-messages has a life span. Clearing the inAppMessagesCache stands for deleting notification messages with an expired life span. In other words, only old notification messages are deleted from the inAppMessagesCache. More recent ones are kept in memory until their life span expires and a new clearInAppMessageCache is called By default, this value is set to Auto. Configuring this value depends how frequently the application will query specific notification messages. In other words, it depends how often you call the API [displayMessage](../-s-m-manager/display-message.md). 

 In a nutshell: 

 * If the application will never query [displayMessage](../-s-m-manager/display-message.md), we recommend keeping this value to default. * If the application use the &quot;In app messages&quot; service, we recommend keeping this value to default. * On the other hand, if the application abuse [displayMessage](../-s-m-manager/display-message.md), we recommend selecting a value higher than the default one. 

 As soon as IAM-service is enabled, the SDK will consider Week as being the default value. Except if you explicitly override the property. In 99% of the cases, you should not override this property as the SDK is smart enough to handle the inAppMessagesCache mechanism by itself.
