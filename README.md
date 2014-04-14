Like the [Cordova Push Notifications Plugin for Android, iOS and WP8](https://github.com/phonegap-build/PushPlugin),
but using the following code in Android's **res/xml/config.xml**:

```xml
<feature name="PushPlugin">
  <param name="android-package" value="com.plugin.gcm.PushPlugin" />
  <param name="onload" value="true" />
</feature>
```