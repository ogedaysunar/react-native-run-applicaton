# React Native Run Application

## iOS

First, you must download project if it is not exists.
*  **git clone "PROJECT_URL"**

If you have project,
* **Open terminal and go to project path (eg. cd /user/git/myProject)**
```
/user/git/myProject username$ npm install 

If you do not have npm, you must download nodejs. https://nodejs.org/en/download/

/user/git/myProject username$ cd ios
/user/git/myProject username$ pod install
``` 
*  **If you see error, delete Pods and Podfile.lock. rm -rf Pods and then rm -rf Podfile.lock -> now run pod install)**
```
/user/git/myProject username$ rm -rf Pods
/user/git/myProject username$ rm -rf Podfile.lock
/user/git/myProject username$ pod install

Then..

/user/git/myProject username$ cd ..
/user/git/myProject username$ npm start -- --reset-cache
```
* **"npm start" command started the react server. You must run the project Xcode or "react-native run-ios" for running project**
```
/user/git/myProject username$ react-native run-ios
``` 
* **You can directly run command which you want to simulator**
```
/user/git/myProject username$ react-native run-ios --simulator="iPhone 6s"
``` 

* **Finally, your simulator look like this!**

![](https://raw.githubusercontent.com/ogedaysunar/react-native-run-applicaton/master/images/phoneBundle.jpg)

* **Your terminal look like this!**

![](https://raw.githubusercontent.com/ogedaysunar/react-native-run-applicaton/master/images/terminaBundle.png)


## Android

* **Very soon**

## License

Ögeday Sunar
ogeday.sunar@gmail.com
intecht.net