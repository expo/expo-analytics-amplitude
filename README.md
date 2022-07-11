# expo-analytics-amplitude

> Source code for the deprecated expo-analytics-amplitude package. This module is removed from Expo SDK in SDK 46. There will be no replacement that works with the classic build service (`expo build`) because [the classic build service has been superseded by **EAS Build**](https://blog.expo.dev/turtle-goes-out-to-sea-d334db2a6b60). With **EAS Build** and [Development Builds](/development/introduction.md), you should use the official [@amplitude/react-native](https://github.com/amplitude/Amplitude-ReactNative) instead.

Provides access to Amplitude (https://amplitude.com/) mobile analytics. This module wraps Amplitude-iOS (https://github.com/amplitude/Amplitude-iOS) and Android (https://github.com/amplitude/Amplitude-Android) SDKs.

# API documentation

- [Documentation for the main branch](https://github.com/expo/expo/blob/main/docs/pages/versions/unversioned/sdk/amplitude.md)
- [Documentation for the latest stable release](https://docs.expo.dev/versions/latest/sdk/amplitude/)

# Installation in managed Expo projects

For [managed](https://docs.expo.dev/versions/latest/introduction/managed-vs-bare/) Expo projects, please follow the installation instructions in the [API documentation for the latest stable release](https://docs.expo.dev/versions/latest/sdk/amplitude/).

# Installation in bare React Native projects

For bare React Native projects, you must ensure that you have [installed and configured the `expo` package](https://docs.expo.dev/bare/installing-expo-modules/) before continuing.

### Add the package to your npm dependencies

```
expo install expo-analytics-amplitude
```

### Configure for iOS

Run `npx pod-install` after installing the npm package.

### Configure for Android

No additional set up necessary.

# Contributing

Contributions are very welcome! Please refer to guidelines described in the [contributing guide](https://github.com/expo/expo#contributing).
