# MLKit Barcode Reader

## Docs
Follow our docs here [https://react-native-community.github.io/react-native-camera/](https://react-native-community.github.io/react-native-camera/)

The comprehensive camera module for React Native.

Supports:

- barcode scanning

### Example import

```jsx
import { RNCamera } from 'react-native-camera';
```

#### How to use master branch?

We recommend using the releases from npm, however if you need some features that are not published on npm yet you can install react-native-camera from git.

**yarn**: `yarn add react-native-camera@git+https://git@github.com/Byvan/react-native-google-mlkit-barcode.git`

**npm**: `npm install --save react-native-camera@git+https://git@github.com/Byvan/react-native-google-mlkit-barcode.git`

##### Permissions

To use the camera,

1) On Android you must ask for camera permission:

```java
  <uses-permission android:name="android.permission.CAMERA" />
```

To enable `video recording` feature you have to add the following code to the `AndroidManifest.xml`:

```java
  <uses-permission android:name="android.permission.RECORD_AUDIO"/>
  <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
  <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```

![5j2jduk](https://cloud.githubusercontent.com/assets/2302315/22190752/6bc6ccd0-e0da-11e6-8e2f-6f22a3567a57.gif)

2) On iOS, you must update Info.plist with a usage description for camera

```xml
...
<key>NSCameraUsageDescription</key>
<string>Your own description of the purpose</string>
...
	
```
