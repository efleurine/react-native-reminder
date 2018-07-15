# react-native-reminder
Some packages - tools and other tips I used to use during development.

## Packages

### react-native-rename

 https://www.npmjs.com/package/react-native-rename
*  this package is very usefull to rename a react-native app and update the package name from the default one install by the cli. Doing this as early as possible (rigth after the generation) ensure a better transition

* `react-native-rename <newName> -b <bundleIdentifier>` With custom Bundle Identifier (Android only. For iOS, please use Xcode) exemaple `react-native-rename "Travel App" -b com.junedomingo.travelapp`
