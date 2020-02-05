# react_native_crash_course

**What is React Native?**

```
(a)React is a Js library/framework for creating user interfaces.


(b)React works together with react Dom in rendering components to the browser.

(c)React Native is a library that can compile react components into native componets/widgets.

(d)React Native allows us to use react to create native ios and android applications.

```

**Advantages of React Native**

**Single codebase**

```
Usually and ios and an android app are completely separate apps.
(Swift-for ios and java/kotlin for android apps)

With react native we can create one single codebase and build for both
platforms.

This saves a lot of time and money.

```

**Components**

```
React Native includes built in components and APIs.

(a)Basic Components->View,Text,Image,TextInput,ScrollView and StyleSheet.

(b)UI->Button,picker,slider,switch.

(c)List Views: FlatList and SectionList.

(d)IOS: ActionSheetIOS,AlertIOS,etc

(e)Android :BackHandler, DatePickerAndroid ,etc

```

**Note Above**

```
There are componets that are platform specific.

Thus you have both agnostic and platform specific components.
```

**Project Concept**

```
Everything in react like props and state is valid in react native.

React native only introduces widgets that may be rendered into the application
since we are working on developing a mobile application.

You can use either functional or classbased components.

This project will employ functional components with hooks.
```

**Requirements**

```
You must have the android sdk to test the application if you are develoing for android
incase youll use the emulator and not a real device.

For ios applications you should have an xcode simulator in order to test.
```

**Installation/SetUp**

```

(a)sudo npm i -g react-native-cli.
Globally installing react native.

(b)react-native init appname.

```

**Project Dependencies**

```
(a)npm i react-native-vector-icons

(b)react-native link react-native-vector-icons


{linking vector icons dependency to the react application is what has happened in the second part.}

Remember that all this is javascript.

```

**Running the App on AndroidEmulator**

```
(a)react-native start

(b)react-native run-android

```

```

**Notes by**

```

Mbugua Caleb.

```

```
