//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMForegroundGcmBroadcastReceiver](index.md)

# SMForegroundGcmBroadcastReceiver

[androidJvm]\
open class [SMForegroundGcmBroadcastReceiver](index.md) : [BroadcastReceiver](https://developer.android.com/reference/kotlin/android/content/BroadcastReceiver.html)

Class implementing the receiver that will listen to connectivity changes. When the device is back online, it will check if some events were not sent to the Selligent Mobile platform due to lack of connectivity and, in that case, will retry sending them. If you do not extend [SMBaseActivity](../-s-m-base-activity/index.md), you have to register and unregister this receiver respectively on the onStart and onStop events of your activities.

## Constructors

| | |
|---|---|
| [SMForegroundGcmBroadcastReceiver](-s-m-foreground-gcm-broadcast-receiver.md) | [androidJvm]<br>constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))<br>Constructor of the class. |

## Functions

| Name | Summary |
|---|---|
| [abortBroadcast](index.md#-1578158536%2FFunctions%2F462465411) | [androidJvm]<br>fun [abortBroadcast](index.md#-1578158536%2FFunctions%2F462465411)() |
| [clearAbortBroadcast](index.md#-547655405%2FFunctions%2F462465411) | [androidJvm]<br>fun [clearAbortBroadcast](index.md#-547655405%2FFunctions%2F462465411)() |
| [getAbortBroadcast](index.md#1852574954%2FFunctions%2F462465411) | [androidJvm]<br>fun [getAbortBroadcast](index.md#1852574954%2FFunctions%2F462465411)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getDebugUnregister](index.md#-2066178064%2FFunctions%2F462465411) | [androidJvm]<br>fun [getDebugUnregister](index.md#-2066178064%2FFunctions%2F462465411)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getIntentFilter](get-intent-filter.md) | [androidJvm]<br>open fun [getIntentFilter](get-intent-filter.md)(): [IntentFilter](https://developer.android.com/reference/kotlin/android/content/IntentFilter.html)<br>It creates the IntentFilter that must be used when registering the receiver. |
| [getResultCode](index.md#-1855658543%2FFunctions%2F462465411) | [androidJvm]<br>fun [getResultCode](index.md#-1855658543%2FFunctions%2F462465411)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getResultData](index.md#485630644%2FFunctions%2F462465411) | [androidJvm]<br>fun [getResultData](index.md#485630644%2FFunctions%2F462465411)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [getResultExtras](index.md#153681375%2FFunctions%2F462465411) | [androidJvm]<br>fun [getResultExtras](index.md#153681375%2FFunctions%2F462465411)(makeMap: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html) |
| [getSentFromPackage](index.md#289542651%2FFunctions%2F462465411) | [androidJvm]<br>open fun [getSentFromPackage](index.md#289542651%2FFunctions%2F462465411)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [getSentFromUid](index.md#-726187215%2FFunctions%2F462465411) | [androidJvm]<br>open fun [getSentFromUid](index.md#-726187215%2FFunctions%2F462465411)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [goAsync](index.md#478464125%2FFunctions%2F462465411) | [androidJvm]<br>fun [goAsync](index.md#478464125%2FFunctions%2F462465411)(): [BroadcastReceiver.PendingResult](https://developer.android.com/reference/kotlin/android/content/BroadcastReceiver.PendingResult.html) |
| [isInitialStickyBroadcast](index.md#-448034677%2FFunctions%2F462465411) | [androidJvm]<br>fun [isInitialStickyBroadcast](index.md#-448034677%2FFunctions%2F462465411)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isOrderedBroadcast](index.md#1250697259%2FFunctions%2F462465411) | [androidJvm]<br>fun [isOrderedBroadcast](index.md#1250697259%2FFunctions%2F462465411)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onReceive](on-receive.md) | [androidJvm]<br>open fun [onReceive](on-receive.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), intent: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html))<br>This method is called when the BroadcastReceiver is receiving an Intent broadcast. |
| [peekService](index.md#-1162131393%2FFunctions%2F462465411) | [androidJvm]<br>open fun [peekService](index.md#-1162131393%2FFunctions%2F462465411)(myContext: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), service: [Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html)): [IBinder](https://developer.android.com/reference/kotlin/android/os/IBinder.html) |
| [setDebugUnregister](index.md#-1900628066%2FFunctions%2F462465411) | [androidJvm]<br>fun [setDebugUnregister](index.md#-1900628066%2FFunctions%2F462465411)(debug: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setOrderedHint](index.md#-1505624509%2FFunctions%2F462465411) | [androidJvm]<br>fun [setOrderedHint](index.md#-1505624509%2FFunctions%2F462465411)(isOrdered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setResult](index.md#1636890479%2FFunctions%2F462465411) | [androidJvm]<br>fun [setResult](index.md#1636890479%2FFunctions%2F462465411)(code: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), data: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), extras: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)) |
| [setResultCode](index.md#-1280302706%2FFunctions%2F462465411) | [androidJvm]<br>fun [setResultCode](index.md#-1280302706%2FFunctions%2F462465411)(code: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setResultData](index.md#-2037197789%2FFunctions%2F462465411) | [androidJvm]<br>fun [setResultData](index.md#-2037197789%2FFunctions%2F462465411)(data: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)) |
| [setResultExtras](index.md#1065610694%2FFunctions%2F462465411) | [androidJvm]<br>fun [setResultExtras](index.md#1065610694%2FFunctions%2F462465411)(extras: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)) |
