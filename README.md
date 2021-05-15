# StopTheSpread
android/ios configurations are linked to Firebase. No need to do it.

## How to use?

1. Download or clone this repo.

2. Install dependencies.

```js
npm install
// or
yarn install
```

3. Go to `src/core/config.js` and replace `FIREBASE_CONFIG` with your own firebase config.

```js
export const FIREBASE_CONFIG = {
  apiKey: "xxx-yyy-zzz", // etc.
  // rest of your firebase config
};
```

4. Run project on iOS / Android.

```js
 npm run ios // npm run android
 // or
 yarn ios // yarn android
```

5. Errors on Mac
If you get an Xcode 65 error which is an xcodebuild error do the following to fix:
```js
sudo gem install cocoapods // if you don't have cocoapods installed
cd ios
pod install
delete build folder // this might not be needed, try next step before doing this or if build folder doesn't exist skip this
cd ..
yarn ios // npm run ios
```

# StopTheSpread Mobile App

To view the server please visit: https://github.com/ContactTracingCU/Stop-the-Spread-Server

> > > > > > > c71f6d06c1d3011c121cb4923a0fd1f5e44abfa9

# Stop-The-Spread
