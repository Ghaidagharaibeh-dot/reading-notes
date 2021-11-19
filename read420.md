

## Basics

- Android apps can be written using java , kotlin or c++.

- .apk is the suffix used to specify an android package which contains all the runtime required contents.

- Each application lives on its own security sandbox, protected by:

1) The android multi-user linux OS on which each application is a different user.

2) Each application is assigned with a unique ID by the system that sets the permissions for that application.

3) Each process in the system operates on its own virtual machine

4) Any process in the application starts only when needed and shut off when not.

- The Android system implements the principle of the least privilege.

## Application Components

- Activities : the interacting interface point with the users.

1) Services : a general purpose entry point for keeping the application running in the background.

1) Broadcast receivers : a component which enables the system to deliver events to the app outside of a regular user flow, allowing the app to respond to system-wide broadcast announcements

2)Content providers : a component which manages a set of application data in a SQLite database which is stored either on the web or in the device storage.

- To activate a component you simply pass it as an asynchronous message called an intent , which binds individual components with each others, there are many separate methods to activate components:
1) to start an activity you pass an intent to startActivity().

2)to start a sevice you pass an intent to startService().

3)to initiate a broadcast you pass an intent to sendBroadcast().


## The Manifest File
All components must be declared in AndroidManifest.xml which is located in the root for the system to recognize them.

what is declard in the manifest file :

- Identifies any user permissions the app requires, such as Internet access or read-access to the user’s contacts.

- Declares the minimum API Level required by the app, based on which APIs the app uses.

- Declares hardware and software features used or required by the app, such as a camera, bluetooth services, or a multi-touch screen.

- Declares API libraries the app needs to be linked against (other than the Android framework APIs), such as the Google Maps library.

## Application Resources

An Android application reuqires more than the code to run, in the resources directory of the application every non-code thing will be stored such as audio , video ,animation , style , colors , images …etc

For every resource the SDK will define a unique integer identifier