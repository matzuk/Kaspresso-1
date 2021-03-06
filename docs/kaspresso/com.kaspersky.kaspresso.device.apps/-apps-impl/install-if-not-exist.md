[kaspresso](../../index.md) / [com.kaspersky.kaspresso.device.apps](../index.md) / [AppsImpl](index.md) / [installIfNotExist](./install-if-not-exist.md)

# installIfNotExist

`fun installIfNotExist(packageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, apkPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Overrides [Apps.installIfNotExist](../-apps/install-if-not-exist.md)

Installs an app via ADB only if [packageName](install-if-not-exist.md#com.kaspersky.kaspresso.device.apps.AppsImpl$installIfNotExist(kotlin.String, kotlin.String)/packageName) is not installed

Required Permissions: INTERNET.

### Parameters

`packageName` - an android package name of the app to be checked.

`apkPath` - a path to the apk to be installed. The apk is hosted on the test server.