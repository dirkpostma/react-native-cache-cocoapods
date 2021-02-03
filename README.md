# Optimize iOS Build times React Native project

This project aims to reduce iOS build times of React Native project.

E.g. by caching derived data or by precompiling cocoapods.

## Getting started

```
git clone https://github.com/dirkpostma/react-native-cache-cocoapods

# setup code signing

cd ios
pod install
bundle install
bundle exec fastlane ios build
```
