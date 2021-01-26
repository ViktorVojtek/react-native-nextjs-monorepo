# React Native Web + NextJs Monorepo

### How to run

- `$ cd react-native-web-monorepo`
- `$ yarn`
- Web
  - [Next.js] `$ yarn workspace web-nextjs dev`
- Mobile
  - [iOS]
    - `$ cd packages/mobile/ios && pod update && pod install && cd -`
    - [CLI]
      - `$ yarn ios`
    - [Xcode]
      - `$ yarn workspace mobile start`
      - `yarn xcode`
      - Press the Run button
  - [Android]
    - [CLI]
      - `$ yarn android`
    - [Android Studio]
      - `$ yarn workspace mobile start`
      - `yarn studio`
      - Press the Run button
