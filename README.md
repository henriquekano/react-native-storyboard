# react-native-storyboard

## Getting started

`$ npm install react-native-storyboard --save`

### Mostly automatic installation

`$ react-native link react-native-storyboard`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-storyboard` and add `Storyboard.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libStoryboard.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.StoryboardPackage;` to the imports at the top of the file
  - Add `new StoryboardPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-storyboard'
  	project(':react-native-storyboard').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-storyboard/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-storyboard')
  	```


## Usage
```javascript
import Storyboard from 'react-native-storyboard';

// TODO: What to do with the module?
Storyboard;
```
