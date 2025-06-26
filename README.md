# Flutter App

A demo app showcasing how Flutter can deliver a great multi-platform experience, targeting iOS, Android, MacOS, Windows, Linux, and web, Flutter App purposefully considers user expectations, input devices and idioms for each platform, ensuring it feels at home on every device.

In addition to forking and reviewing the [MIT licensed](LICENSE.md) code available here.

### Installation

If you're new to Flutter the first thing you'll need is to follow the [setup instructions](https://flutter.dev/docs/get-started/install). 

Once Flutter is setup, you can use the latest `stable` channel:
 * Run `flutter channel stable`
 * Run `flutter upgrade`

Once you're on `dev` and desktop is enabled, you're ready to run the app:
* `flutter run -d windows`
* `flutter run -d macos`
* `flutter run -d linux`
* `flutter run -d android`
* `flutter run -d ios`
* `flutter run -d web`

If you re-start your IDE, you should also see a new launch option for your current desktop platform.

### Client Keys
This repo includes a set of Keys for Cloudinary and Firebase that are on the free pricing plans. Depending on traffic, these may reach their limit. If that happens, you will need to provide your own keys in order to run the app locally, those can be found in `AppKeys.dart`. These limits should refresh each month, so your mileage will vary here.

### License

This application is released under the [MIT license](LICENSE.md). You can use the code for any purpose, including commercial projects.

[![license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

