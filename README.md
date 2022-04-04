# VRCTeslasuitIntegration_OSC
A standalone application that allows for the TESLASUIT (DK1) to be used in VRChat via OSC. 11-point tracking, advanced full body haptics and biometric data integrations are supported. 

## Requirements:

- VRChat with the IK 2.0 Update (Currently Open Beta)
- TESLASUIT DK1/M1/Founders Edition
- TESLASUIT SDK 1.7.xx+
- Windows 10 1902+
- [Microsoft .NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- Base PC Spec (Full tracking support, partial haptics support, full biometrics support):
  - AMD Ryzen 3600X/Intel equivalent
  - 16GB RAM
  - GTX 1080Ti or AMD equivalent
- Recommended PC Spec (Full tracking support, full AI driven haptics support, full biometrics support):
  - AMD Ryzen 5800X/Intel Equivalent
  - 64GB RAM
  - RTX 3080 (RTX is a requirement for Nvidia AI tensor acceleration)
- Competent Unity knowledge as support needs to be integrated into your avatar to take advantage of most features. As of now the process is mostly manual. An automatic setup/appliction script is in the works. A unity prefab is included with all releases with all assets required for full TESLASUIT support. 3 int value + Single int value options are available for HR display. Special thanks to 200TigersBloxed and Sonic853 for their public repositories that helped immensely with this. VRChat IK 2.0 supports 10 point tracking natively. 11-Point (Chest tracking) is achieved via rotation constraints on the chest bone.

Screenshots:
![Screenshot 1 jpg](https://user-images.githubusercontent.com/97592971/161565667-9ed49080-2d13-4bad-aacf-3453c04d7200.png)

## More Info:

(Placeholder. Currently Closed Source).

Teslasuit.io

## Credits

* [VRChat Community](https://github.com/vrchat-community)
* VRC OSC (Discord Community)
* [200Tigersbloxed/HRtoVRChat_OSC](https://github.com/200Tigersbloxed/HRtoVRChat_OSC)
* [Sonic853/Pulsoid-To-VRChat-OSC](https://github.com/Sonic853/Pulsoid-to-VRChat-OSC)
* [TESLASUIT](https://www.teslasuit.io/)
* [Nvidia Developer](https://developer.nvidia.com)
* [Somnium Space](https://somniumspace.com/)
* [Google Brain Team/TensorFlow API](https://www.tensorflow.org)
