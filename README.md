# AGC Mockup (Phase 1)

This mockup is slightly modified from the Flutter Skeleton template app. Differences include:

* Elimination of the src/ directory
* Elimination of localization
  * deleted flutter_localization and generate: true from pubspec.yml.
  * deleted i10n.yml file
  * deleted locationization directory
* Eliminated restoration
* Addition of pages for various garden-related functions

## Installation

After downloading, cd into the directory and invoke:

```
flutter run
```

On my platform, that brings up the iOS simulator and the following:

```
% flutter run
Launching lib/main.dart on iPhone 13 Pro in debug mode...
Running Xcode build...                                                  
 └─Compiling, linking and signing...                         3.2s
Xcode build done.                                           14.4s
[VERBOSE-2:FlutterDarwinContextMetalImpeller.mm(37)] Using the Impeller rendering backend.
Syncing files to device iPhone 13 Pro...                           119ms

Flutter run key commands.
r Hot reload. 🔥🔥🔥
R Hot restart.
h List all available interactive commands.
d Detach (terminate "flutter run" but leave application running).
c Clear the screen
q Quit (terminate the application on the device).

A Dart VM Service on iPhone 13 Pro is available at: http://127.0.0.1:63610/L5Qxu9BkbG0=/
The Flutter DevTools debugger and profiler on iPhone 13 Pro is available at:
http://127.0.0.1:9101?uri=http://127.0.0.1:63610/L5Qxu9BkbG0=/
```

## Screenshots

Here are screen shots that illustrate this mockup. We use the flutter_markdown package to provide information on what should appear in a page when we haven't gotten around to actually mocking up the contents.

Click on any screen shot to see it full-size.

<p style="text-align: center">
  <img src="./README-screenshots/screen-1.png" width="25%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/screen-2.png" width="25%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/screen-3.png" width="25%">

  <img src="./README-screenshots/screen-4.png" width="25%">
  <img src="./README-screenshots/screen-5.png" width="25%">
</p>
