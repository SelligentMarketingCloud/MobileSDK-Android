//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMSettings](index.md)/[ConfigureGeolocation](-configure-geolocation.md)

# ConfigureGeolocation

[androidJvm]\
open var [ConfigureGeolocation](-configure-geolocation.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

This will tell the SDK to use the geolocation. Default is false. 

 If you didn't set &quot;enableOnFirstRun&quot; to false in the plotconfig.json file, geolocation will enable right away, asking for the permission if needed, monitoring geofences and displaying notifications. Otherwise, you will need to call [enableGeolocation](../-s-m-manager/enable-geolocation.md). 

 NB: In the plotconfig.json file, if &quot;enableOnFirstRun&quot; or &quot;automaticallyAskLocationPermission&quot; is set to false, you have to ask for the location permission yourself. The default value for these settings is true.

#### Deprecated

functionality removed
