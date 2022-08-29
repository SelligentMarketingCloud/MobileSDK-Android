//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMWebViewNavigationOverride](index.md)

# SMWebViewNavigationOverride

[androidJvm]\
interface [SMWebViewNavigationOverride](index.md)

Implement this interface if you want to override the navigation in the WebViews displayed by the In-App messages. It will allow you to check the link clicked by the user and decide how the SDK will handle (or not) the navigation.

## Functions

| Name | Summary |
|---|---|
| [shouldHandleURL](should-handle-u-r-l.md) | [androidJvm]<br>abstract fun [shouldHandleURL](should-handle-u-r-l.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), url: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>This method will be called when a link is clicked in a WebView displayed by an In-App message. |
