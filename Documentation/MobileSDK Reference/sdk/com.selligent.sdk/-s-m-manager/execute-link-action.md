//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[executeLinkAction](execute-link-action.md)

# executeLinkAction

[androidJvm]\
open fun [executeLinkAction](execute-link-action.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), link: [SMLink](../-s-m-link/index.md), content: [SMInAppContent](../-s-m-in-app-content/index.md))

This method will execute the action attached to the given [SMLink](../-s-m-link/index.md) of the given [SMInAppContent](../-s-m-in-app-content/index.md). It will also send an event to the platform to inform the link was clicked. Use this method if you do not want to implement our Fragments.

#### Parameters

androidJvm

| | |
|---|---|
| context | the current [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html). |
| link | the [SMLink](../-s-m-link/index.md) containing the action to execute. |
| content | the corresponding [SMInAppContent](../-s-m-in-app-content/index.md). |
