Simple test to check if `onChangeVisibleRows` is called for ListView on Android.

```
npm install
open ios/ListViewTest.xcodeproj/ #and hit run in XCode
react-native run-android
```

In the simulator, open the *dev menu*, and *Debug in Chrome*.

If `onChangeVisibleRows` is properly called, it will be displayed in the console with its arguments (visibleRows first and the ones with a changing state then).

This is done properly on iOS but not on Android (with React Native 0.15.0).
