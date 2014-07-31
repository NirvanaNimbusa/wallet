# Blockchain Merchant
### Brought to you by [blockchain.info](https://blockchain.info/)
[Blockchain Merchant](https://play.google.com/store/apps/details?id=info.blockchain.merchant) makes it easy to accept Bitcoin payments at any retail location. It's the ideal point-of-sale (POS) solution for restaurants, bars, cafés, and all retail merchants accepting Bitcoin.
Just set up the Blockchain Merchant app with your bitcoin wallet address and your business can start receiving bitcoin payments via the Blockchain API.

![Screenshot](https://lh3.ggpht.com/SpsOhGSz89sJ9Tm_wuANBlFLicxVYsVbbov40cTkg6A3Xb1nQbEN2v6xRPxS1J4G_30=h450)   ![Screenshot](https://lh6.ggpht.com/PrI6ne8oT0qCeUy2qQEQw4R1dIpGot2efn5iWm4fNwADH6z5jPol3308hJzvP7UYe3I=h450) ![Screenshot](https://lh3.ggpht.com/apAMRM_fes2swapXcg4OMtjk9iyUoPcFoewcMfi_6jJeKjmRwJswx0qyaP2vz7RDt2Ze=h450)

## Maven build process

This project is Maven compatible. In order to build an APK package using Maven, the following items need to be present:

* Maven 3.1
* Android SDK 19
* The ANDROID_HOME environment variable needs to be set and point to the root of the SDK installation directory.

Build steps:

* (first time setup only) `mvn install:install-file -Dfile=%ANDROID_HOME%\platforms\android-19\android.jar -DgroupId=com.google.android -DartifactId=android -Dversion=4.4.2 -Dpackaging=jar -DgeneratePom=true`
* `mvn package`

The above steps will create an APK artifact in the `target` directory.

## Contributing
There are still many translations needed. [How to translate Android Apps.](https://developer.android.com/training/basics/supporting-devices/languages.html#CreateDirs)
