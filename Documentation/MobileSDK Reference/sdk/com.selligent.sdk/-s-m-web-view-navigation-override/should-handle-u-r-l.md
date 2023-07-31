//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMWebViewNavigationOverride](index.md)/[shouldHandleURL](should-handle-u-r-l.md)

# shouldHandleURL

[androidJvm]\
abstract fun [shouldHandleURL](should-handle-u-r-l.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), url: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [SMWebViewNavigationOption](../-s-m-web-view-navigation-option/index.md)

This method will be called when a link is clicked in a WebView displayed by an In-App message. How the navigation proceeds will depend on the value returned.

#### Return

the [SMWebViewNavigationOption](../-s-m-web-view-navigation-option/index.md) indicating how the SDK must handles the navigation

#### Parameters

androidJvm

| | |
|---|---|
| context | The Context of the call (the Activity containing the WebView) |
| url | The URL String that was clicked |
