# Agora React Native Demo

Quickstart for group video calls on react-native using Agora.io SDK

## Installation & Usage

- Go to https://dashboard.agora.io/en/signup, make an account and login to the dashboard.
- Navigate to the project list tab under projects and create a new project by clicking the green button.
- Copy your App ID and save it somewhere.
- Install NPM and Node.js if you don't have it already.
- Download and extract the zip file from master branch.
- Run `npm install` or use yarn to install the app in the unzipped directory.
- Go to `./components/Video.js` and edit line 18 to put your App ID from the dashboard as `AppID: 'exampleAppID'`
- Execute `react-native link react-native-agora`.
- Connect your device or start an AVD then run `react-native run-android` to start the app.

The app uses channel-name as `channel-x`.