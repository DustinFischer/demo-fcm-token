# demo-fcm-token
Demo project to retrieve a device / registration token for FCM cloud messaging.

* This is a fork of https://github.com/xtrinch/fcm-django-web-demo
* Has been stripped and modified for demo purposes
* Used to  **retrieve an FCM registration token** only

***
The Firebase Cloud Messaging quickstart demonstrates how to:
- Request permission to send app notifications to the user.
- Receive FCM messages using the Firebase Cloud Messaging JavaScript SDK.

Introduction
------------

- [Read more about Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/)

Getting Started
---------------

1. Set up your project on the [Firebase Console](https://console.firebase.google.com).
2. Paste initialization snippet into `index.html` with the one generated from
   the Firebase Console **Overview > Add Firebase to your web app**. See TODO in
   `index.html`.
3. Use the generated Instance ID token to send an HTTP request to FCM that
   delivers the message to the web application, inserting appropriate values
   for [YOUR-SERVER-KEY](https://console.firebase.google.com/project/_/settings/cloudmessaging)
   and YOUR-IID-TOKEN.


### App focus
The browser gives your app focus when both:

1. Your app is running in the currently selected browser tab.
2. The browser tab's window currently has focus, as defined by the operating system.

Support
-------

https://firebase.google.com/support/

License
-------

© Google, 2016. Licensed under an [Apache-2](../LICENSE) license.
