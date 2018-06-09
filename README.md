# DJIMobileOnboard

## Introduction

Barebone application for sending specific data to the Onboard controller SDK
through button clicks on an Android app.

## Requirements

 - Android Studio 2.0+
 - Android System 4.1+
 - DJI Android SDK 4.5.1

## Installation
 - Install Android Studio <https://github.com/uw-it-aca/spacescout-android/wiki/1.-Setting-Up-Android-Studio-on-Ubuntu>
 - Prepare for device <https://developer.android.com/studio/run/device>.
 - Create an ID for the user app and modify the ID in `AndroidManifest.xml` at `com.dji.sdk.API_KEY`.
 - To prepare the environment, please take a look at the tutorial <https://developer.dji.com/mobile-sdk/documentation/application-development-workflow/workflow-integrate.html>.

## Modifications

 - Buttons can be added in `activity_main.xml`.
 - Code can then be associated in `MainActivity.java`.

## License

DJIMobileOnboard is available under the MIT license. Please see the LICENSE file for more info.

## Contact

Alberto Quattrini Li <albertoq@cse.sc.edu>
