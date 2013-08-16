flurry-phonegap-plugin
======================

Forked from [CarsonF](https://github.com/CarsonF/flurry-phonegap-plugin)

Updated to be installable via plugman/cordova-cli and compatible with cordova 2.9.0.

Included latest Flurry libraries (Android: 3.2.1, iOS: 4.2.2)


=====

Phonegap plugin for Flurry mobile analytics

You really need to be careful that you pass the correct values to the methods. In particular, all event parameters must be
in an NSDictionary that only contains strings, and remember that in Objective C booleans are Yes and No.

Here's how to install the plugin:

1. Register with Flurry and get an App key
2. Install plugin with plugman or cordova-cli
3. Call the startSession() method, with your app key, after the device is ready
4. Call the other Flurry methods as appropriate.
