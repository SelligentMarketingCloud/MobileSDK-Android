//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMInAppRefreshType](index.md)

# SMInAppRefreshType

[androidJvm]\
enum [SMInAppRefreshType](index.md)

Enum with the different values for the refresh of the In App messages and In Ap contents. Messages/contents will be retrieved when the application becomes active (if In App messages/contents are enabled) if the last fetch was older than the refresh type. Minutely is there for testing purposes ONLY. We do NOT recommend using it in production.

## Entries

| | |
|---|---|
| [None](-none/index.md) | [androidJvm]<br>[None](-none/index.md) |
| [Minutely](-minutely/index.md) | [androidJvm]<br>[Minutely](-minutely/index.md) |
| [Hourly](-hourly/index.md) | [androidJvm]<br>[Hourly](-hourly/index.md) |
| [Daily](-daily/index.md) | [androidJvm]<br>[Daily](-daily/index.md) |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>open fun [valueOf](value-of.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [SMInAppRefreshType](index.md) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[SMInAppRefreshType](index.md)&gt; |
