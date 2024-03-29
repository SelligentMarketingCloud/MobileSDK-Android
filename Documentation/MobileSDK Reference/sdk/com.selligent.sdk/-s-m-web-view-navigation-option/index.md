//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMWebViewNavigationOption](index.md)

# SMWebViewNavigationOption

[androidJvm]\
enum [SMWebViewNavigationOption](index.md)

Enum used by [shouldHandleURL](../-s-m-web-view-navigation-override/should-handle-u-r-l.md) to tell the SDK how to handle the navigation: - ResumeNavigation: the navigation will continue in the WebView like usual. - StopNavigation: the navigation will stop and the Activity displaying the WebView will close. Use this if you want to handle the navigation yourself. - StopNavigationAndExecuteDeeplink: the navigation will stop, the Activity displaying the WebView will close and the SDK will start another Activity to execute the deeplink.

## Entries

| | |
|---|---|
| [ResumeNavigation](-resume-navigation/index.md) | [androidJvm]<br>[ResumeNavigation](-resume-navigation/index.md) |
| [StopNavigation](-stop-navigation/index.md) | [androidJvm]<br>[StopNavigation](-stop-navigation/index.md) |
| [StopNavigationAndExecuteDeeplink](-stop-navigation-and-execute-deeplink/index.md) | [androidJvm]<br>[StopNavigationAndExecuteDeeplink](-stop-navigation-and-execute-deeplink/index.md) |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>open fun [valueOf](value-of.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [SMWebViewNavigationOption](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMWebViewNavigationOption](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. This method may be used to iterate over the constants. |
