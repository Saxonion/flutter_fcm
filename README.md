# flutter_fcm

flutter example for Firebase Clouding Messaging.

## Prepare

1. Register account [firebase](https://firebase.google.cn/)

## Start

1. add dependencies in `pubspec.yaml`

```yaml
  firebase_core: ^1.6.0
  firebase_messaging: ^10.0.0
  firebase_messaging_platform_interface: ^3.1.6
  flutter_local_notifications: ^8.2.0
```

2. add classpath in `android/build.gradle` file

```
classpath 'com.google.gms:google-services:4.3.2'
```

3. add dependencies implementation & plugin in `android/app/build.gradle` file

```
dependencies {
  implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
  implementation 'com.google.firebase:firebase-messaging:20.1.0'
  implementation platform('com.google.firebase:firebase-bom:29.2.0')
}
```

```
apply plugin: 'com.google.gms.google-services'
```

4. import `firebase.dart` into `main.dart`
