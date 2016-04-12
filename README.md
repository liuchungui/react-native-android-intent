#react-native-android-intent
Like [android-intents](https://github.com/d-tarasov/android-intents), this is a react-native library that helps you call thirdparty apps to do generic work instead of you.

#Install
```
npm install react-native-android-intent --save
rnpm link
```

#Usage
```
    Intent.open(filePath, isOpen => {
      if(isOpen) {
        console.log("Can open");
      }
      else {
        console.log("can't open");
      }
    });
```


