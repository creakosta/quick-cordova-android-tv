# quick-cordova-android-tv

NOTE: This is a plugin forked from lycwed (see lycwed-cordova-plugin-android-tv), and is essentially the same thing, with a few tweaks made to allow for it to use the same Android activity as any cordova app which uses MainActivity.

Cordova plugin to manage app for Android TV.

## Install

`cordova plugin add quick-cordova-android-tv`

## Requirements

Include banners in config.xml at varying sizes as splash images. These will be automatically added to various 'drawable' folders.

Then add in your config.xml in platform android :

```xml
        <edit-config file="app/src/main/AndroidManifest.xml" mode="merge" target="/manifest/application">
            <application android:banner="@drawable/screen" />
            <application android:isGame="true" />
        </edit-config>
```
