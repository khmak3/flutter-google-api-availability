# Flutter Google Api Availability Plugin  

[![pub package](https://img.shields.io/pub/v/flutter-google-api-availability.svg)](https://pub.dartlang.org/packages/flutter-google-api-availability)

A Flutter plugin to check the availability of Google Play services on the current device. 

Branch  | Build Status 
------- | ------------
develop | [![Build Status](https://travis-ci.com/BaseflowIT/flutter-google-api-availability.svg?branch=develop)](https://travis-ci.com/BaseflowIT/flutter-google-api-availability)
master  | [![Build Status](https://travis-ci.com/BaseflowIT/flutter-google-api-availability.svg?branch=master)](https://travis-ci.com/BaseflowIT/flutter-google-api-availability)

## Features

* Check the availability of Google Play services (on Android only).

## Usage

To use this plugin, add `flutter-google-api-availability` as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/). For example:

```yaml
dependencies:
  flutter-google-api-availability: '^1.0.0'
```

> **NOTE:** There's a known issue with integrating plugins that use Swift into a Flutter project created with the Objective-C template. See issue [Flutter#16049](https://github.com/flutter/flutter/issues/16049) for help on integration.

## API

### GoogleApiAvailability

To check the availability of Google Play services on the current device, you can use the `checkGooglePlayServicesAvailability` method. This could be helpful to provide a more friendly experience to users in case an user-action is required to enable support for Google Play services (More information can be found [here](https://developers.google.com/android/guides/setup)). 

``` dart
import `package:google_api_availability/google_api_availability.dart`;

GooglePlayServicesAvailability availability = await GoogleApiAvailability().checkGooglePlayServicesAvailability();
```

See also the [example](example/lib/main.dart) project for a complete implementation.

## Issues

Please file any issues, bugs or feature request as an issue on our [GitHub](https://github.com/BaseflowIT/flutter-google-api-availability/issues) page.

## Want to contribute

If you would like to contribute to the plugin (e.g. by improving the documentation, solving a bug or adding a cool new feature), please carefully review our [contribution guide](CONTRIBUTING.md) and send us your [pull request](https://github.com/BaseflowIT/flutter-google-api-availability/pulls).

## Author

This flutter-google-api-availability plugin for Flutter is developed by [Baseflow](https://baseflow.com). You can contact us at <hello@baseflow.com>