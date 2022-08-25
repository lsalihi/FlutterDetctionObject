# ai_vision_plus

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Fix ':tflite'  No signature of method .android() is applicable for argument types
Update android/build.gradle  : use  com.android.tools.build:gradle:4.1.0
    dependencies {
        classpath 'com.android.tools.build:gradle:4.1.0'
        ...
    }

Update android/app/build.gradle => set minSdkVersion to 19
    defaultConfig {
        ...
        minSdkVersion 19
        ...
    }

