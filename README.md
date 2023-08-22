
react-native-fabric-crashlytics
===============================

Reports javascript exceptions in React Native to the Crashlytics server, using the react-native-fabric library.

Usage
-----

To use, add this code to your index.ios.js and index.android.js (or some library included by both).

```
// Already assumes that Fabric is initialized/configured properly in the iOS and Android app startup code.
import crashlytics from 'react-native-fabric-crashlytics';
crashlytics.init();
```

Crash analysis in React Native is the process of identifying and resolving the causes of errors and crashes in your app. 
There are many tools and techniques that can help you with crash analysis, such as:

UXCam: A tool that captures user sessions, screen recordings, heatmaps, and analytics to help you understand user behavior and improve user experience1.

Raygun: A tool that monitors your app performance, tracks errors and crashes, and provides actionable insights to fix them1.

Firebase Crashlytics: A tool that collects crash reports, stack traces, device information, and user feedback to help you diagnose and fix issues12.

Sentry: A tool that captures errors, exceptions, and performance issues across your app stack and provides real-time alerts and debugging information1.

Logcat: A command-line tool that prints messages from the Android system and your app to the console. It can help you debug native crashes in React Native apps3.
