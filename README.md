# React Native Run Application

## iOS

First, you must download project if it is not exists.
* git clone "PROJECT_URL"

If you have project,
* Open terminal and go to project path (eg. cd /user/git/myProject)
* npm install (if you do not have npm, you must download nodejs. https://nodejs.org/en/download/)
* cd ios
* pod install (if you see error, delete Pods and Podfile.lock. rm -rf Pods and then rm -rf Podfile.lock -> now run pod install)
```
/user/git/myProject username$ pod install
/user/git/myProject username$ rm -rf Pods
/user/git/myProject username$ rm -rf Podfile.lock

Then..

/user/git/myProject username$ pod install
``` 
* cd ..
* npm start -- --reset-cache (This command started the react server. You must run the project xCode or "react-native run-ios" for running project)
```
/user/git/myProject username$ npm start -- --reset-cache 
``` 
* You can directly run command which you want to simulator
```
/user/git/myProject username$ <b>react-native run-ios --simulator="iPhone 6s"<b>
``` 

* Finally, your simulator look like this!
![](https://raw.githubusercontent.com/eneko/Ninety-Nine-Swift-Solutions/master/.github/Screenshot%202018-03-06%2021.43.03.png)

## Android


## Installation

See: https://reactnavigation.org/docs/en/getting-started.html

## Code of conduct

This library has adopted a Code of Conduct that we expect project participants to adhere to. Please read the [full text](https://github.com/react-community/react-navigation/blob/master/CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

## License

React Navigation is licensed under the [MIT](https://github.com/react-community/react-navigation/blob/master/LICENSE).
