# Android AR Application for Mixed Reality Lab WS19/20
AR application that recognizes specific image and displays a walking 3D model on top of the image
## Prerequisites
* [Unity 2017.4.34](https://unity3d.com/get-unity/download/archive)
* [Visual Studio Community 2017](https://visualstudio.microsoft.com/vs/older-downloads/)
## Installation/Setup instructions
### Needed modules for Unity :
 - MonoDevelop/Unity Debugger
 - Android Build Support
 - Windows Store .NET Scripting Backend
 - Windows Store IL2CPP Scripting Backend
 - Vuforia Augmented Reality Support
### Needed workloads for Visual Studio Community  :
 - .NET desktop development
 - Desktop development with C++
 - Universal Windows Platform development
 - Game development with Unity (deselect Unity Editor)
## Deployment
- Clone/Download MiniatureFigure-Hallolens Unity project folder
### Running in Unity Editor
- Open project folder with Unity and run in editor using webcam as camera
### Running on Android Phone
- Open project folder in Unity
- Download the Android [SDK Tools](https://developer.android.com/studio)
- Install Java JDK [Java SE Development Kit 8.0 Update 231](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- Select the Android SDK and Java JDK paths in Unity external tools preferences.
- Select your Android version in player settings
- Enable USB debugging on phone and connect device to PC ([Help](https://www.embarcadero.com/starthere/xe5/mobdevsetup/android/en/enabling_usb_debugging_on_an_android_device.html))
- Build and run on Unity and try the application on your Android device
- Use following image to test AR App
![Image for testing](https://github.com/rwth-acis/MiniatureFigure-Hallolens/blob/master/imageForARApp.jpg)
## Resources Used
- Unity 2017.4.34
- [Vuforia](https://developer.vuforia.com/)
- Visual Studio Community 2017
- "Figure" unitypackage given by Mixed Reality Lab Team
## Authors
Steven Zambrano

Danylo Bekhter
