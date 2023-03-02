# Battery Optimization App

Our Project for 2022 Mobile Action Hackathor event <br/>
This is a mobile application written in React Native that helps users optimize their battery usage.

## The app has been designed to:
Calculate the runtime for video playback, streaming, and audio playback on different iPhone models ranging from iPhone 11 to iPhone 14. Based on the calculated runtime, the app suggests changes to the phone's settings that can help decrease battery usage.

## Features

- Calculate the runtime for video playback, streaming, and audio playback on different iPhone models.
- Change settings such as Wi-Fi connection, low power mode, cellular data connection quality, airplane mode, Bluetooth, and brightness to decrease battery usage
- Provide feedback on whether the current state of the device is optimal for battery usage or not.
- Track the location of the user and detect whether the current temperature is optimal for the device.
- Check if the phone is in the latest software update and warn the user if it is not.
- Give local notifications if the app is not in the optimal interval of charging.

## Installations

To use the app, you need to have Expo installed on your computer. Follow these steps to install the app:
1- Clone the repository on your local machine:

```bash
git clone git@github.com:YigitEkin/IOS-battery-optimization-app.git
```

2- Install the app's dependencies:

```bash
cd frontend && yarn install
```

3- Start the app:

```bash
yarn ios
```

Download the Expo client app on your mobile device. Scan the QR code displayed in the terminal with the Expo client app to launch
