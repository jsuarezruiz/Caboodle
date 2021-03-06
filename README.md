# Microsoft Caboodle

Microsoft Caboodle gives developers essential cross-platform APIs for their mobile applications. 

iOS, Android, and UWP offer unique operating system and platform APIs that developers have access to all in C# leveraging Xamarin. It is great that developers have 100% API access in C# with Xamarin, but these APIs are different per platform. This means developers have to learn three different APIs to access platform specific features. With Caboodle developers have a single cross-platform API that works with any iOS, Android, or UWP application that can be accessed from shared code no matter how the user interface is created.

## Build Status
[![Build Status](https://jenkins.mono-project.com/buildStatus/icon?job=Components-Caboodle)](https://jenkins.mono-project.com/view/Components/job/Components-Caboodle/)

## Installation
Microsoft Cabooble is available on MyGet via:  

## Supported Platforms
Caboodle is focused on the following platforms for our first release:
 - iOS (10+)
 - Android (4.4+)
 - UWP (Fall Creators Update+)

## Current Features:
The following cross-platform APIs are planned for our first release:
 - Permissions
 - Preferences
 - Geolocation
 - Connectivity
 - Device Capabilities
 - Device Information
 - Email
 - SMS
 - Battery
 - Share Text
 - Open Browser
 - File System Helpers
 - Magnetometer
 - Gyroscope
 - Compass
 - Accelerometer
 - Phone Dialer
 - Clipboard
 - Text-to-Speech

## Future Feature Plans:
 - Media Picker
 - Bluetooth
 - Audio
 - Open Maps
 - Keystore/Keychain
 - Store Review
 - Vibrate
 
## Contributing
Please read through our [Contribution Guide](CONTRIBUTING.md).

## Building Caboodle
Caboodle is built with the new SDK style projects with multi-targeting enabled. This means that all code for iOS, Android, and UWP exist inside of the Caboodle project. 

If building on Visual Studio 2017 simply open the solution and build the project. 

If using Visual Studio for Mac the project can be built at the command line with MSBuild. To change the project type that you are working with simply edit Caboodle.csproj and modify the TargetFrameworks for only the project type you want to use.

## License
Please see the [License](LICENSE).
