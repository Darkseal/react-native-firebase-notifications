# react-native-firebase-notifications
React Native sample app for Android and iOS with Push Notifications support for Android and iOS using Firebase SDK and API.

## Introduction

This sample app has been made using the following five-part tutorial:

* https://www.ryadel.com/en/react-native-push-notifications-setup-firebase-1/

Which shows how we can create **a sample React Native app** that will be capable of receiving Push Notifications using Firebase. 

The tutorial can be a great headstart for React Native beginners, yet also for those intermediate or experienced developers who want to know more about push notifications: how they work, what are their best usage scenarios and how much they can be an improvement for almost any mobile app.

## Push Notifications Workflow

The following diagram depicts the underlying **Push Notification Workflow** implemented by this app:

![img](https://www.ryadel.com/wp-content/uploads/2019/07/Push-Notifications-Workflow.png)

## Topics covered

For the sake of simplicity the tutorial has been splitted into multiple parts, each one dedicated to a specific sub-topic:

* **[Part 1 of 5](https://www.ryadel.com/en/react-native-push-notifications-setup-firebase-1/)**: Understanding Push Notifications, in which we’ll try to understand what push notifications actually are and the impact they could have (when used properly) on a typical client-server app.
* **[Part 2 of 5](https://www.ryadel.com/en/react-native-push-notifications-setup-firebase-2/)**: Setup React Native and Firebase, where we’ll deal with the installation and configuration of our whole development stack: React Native, the Firebase SDK and the Visual Studio Code environment, together with the required settings to get our app ready to work with Android and iOS.
* **[Part 3 of 5](https://www.ryadel.com/en/react-native-push-notifications-setup-firebase-3/)**: Configure the Firebase Service, in which we’ll create the Firebase Project and configure the Firebase Push Notification Services to ensure that our React Native app will be able to receive push notifications through the Firebase API on any Android and iOS device.
* **[Part 4 of 5](https://www.ryadel.com/en/react-native-push-notifications-setup-firebase-4/)**: Design and Test the React Native UI, where we’ll test our front-end skills by laying out a React-Native UI in order to make our app actually able to receive push notifications and send HTTP requests to the server to remotely keep track of our actions – and possibly fire subsequent push notifications to other clients.
* **[Part 5 of 5](https://www.ryadel.com/en/react-native-push-notifications-setup-firebase-5/)**: Server-Side Handler, in which we’ll use ASP.NET Core to create a sample, lightweight web service that will be able to receive HTTP requests issued by the clients and/or feed them with push notifications through the Firebase API.

## Screenshots

Here's a screenshot of the app initial view on an Android device:

![img](https://www.ryadel.com/wp-content/uploads/2019/12/react-native-firebase-notifications-android-app-screenshot-1.jpg)

And here's a screenshot showing the full push notifications roundtrip:

![img](https://www.ryadel.com/wp-content/uploads/2019/12/react-native-firebase-notifications-android-app-screenshot-1.jpg)

The app sends and receives push notifications using the **Firebase *send* API** or an external back-end Web Service built with .NET Core.

## License

This project has been released under MIT license and is free to use for any educational and/or commercial purposes.

## Useful links

* https://www.ryadel.com/ 
