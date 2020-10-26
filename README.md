<a href="https://github.com/Solido/awesome-flutter">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>

# Chatting App

Chatting App - A minimalist, locked-down one-to-one chat app.

## Usage

* [Flutter - Get Started](https://flutter.dev/docs/get-started/install)
* Since this is a Firebase dependent project, create a Firebase Project and enable
  * Firebase Phone Authentication (for authentication)
  * Cloud Firestore (not Realtime Database)
  * Firebase Storage (for storing images)
  * Firebase In-App Messaging (for custom messages)
* After enabling the above features, download the `google-services.json` and paste it in `android/app` folder.
* Do `flutter packages get` to get the packages.
* Use a device or an emulator and run `flutter run`.

## Notifications

1. Enable FCM in your Firebase Console.
2. Notifications use Cloud Functions. Copy the `functions` directory to the root of your project.
3. Do `firebase deploy --only functions` You need to have `firebase-cli` installed for this command to execute.

## Screenshots

![Screenshot #1](https://i.imgur.com/j6K1iKg.jpg)

