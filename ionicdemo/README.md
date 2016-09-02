Ionic App Base
=====================

A starting project for Ionic that optionally supports using custom SCSS.

## Using this project

ionic version 2.0.0 

to update
```bash
npm install -g ionic

```
start your app development

```bash
ionic platform add android
ionic plugin add cordova-plugin-broadcaster
cordova plugin add ionic-plugin-keyboard
```


insert MainActivity.java and AMReceiver.java to Android Studio 

copy ./src/com/* to ./platforms/android/src/com


```
ionic platform update android 
ionic build  android
ionic run android
```

of

import ionic project to android studio 

build and run

## Debug

ionic can be debugged with Android Phone


## Publish 

```bash
cordova build --release android
```
or

 public by android studio


## Issues
