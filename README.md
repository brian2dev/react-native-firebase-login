﻿# React Native Firebase Login Template

## How to use?

1. Download or clone this repo.

2. Install dependencies.

```js
npm install
// or
yarn install
```

3. Go to `src/core/config.tsx` and replace `FIREBASE_CONFIG` with your own firebase config.

```js
export const FIREBASE_CONFIG = {
  apiKey: "xxx-yyy-zzz" // etc.
  // rest of your firebase config
};
```

4. Run project on iOS / Android.

```js
 npm run ios // npm run android
 // or
 yarn ios // yarn android
```

Project was created using [Expo](https://expo.io/). If you want standard native project please run following command:

```js
expo eject
```

## Preview

![homescreen](https://raw.githubusercontent.com/venits/react-native-market/master/assets/firebase-login-template/homescreen.png)