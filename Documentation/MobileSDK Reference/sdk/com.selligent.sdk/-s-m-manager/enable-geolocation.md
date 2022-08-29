//[sdk](../../../index.md)/[com.selligent.sdk](../index.md)/[SMManager](index.md)/[enableGeolocation](enable-geolocation.md)

# enableGeolocation

[androidJvm]\
open fun [enableGeolocation](enable-geolocation.md)()

Enables the geolocation functionality. It will be enabled until [disableGeolocation](disable-geolocation.md) is called. It will keep going even if the app or the device is restarted. The goal is to provide users with an opt-in. WARNING: this method should only be called if &quot;enableOnFirstRun&quot; is set to &quot;false&quot; in the plotconfig.json file. **With the default configuration, you do not have to call it**.
