# awesome-hyperloop-titanium

### A curated list of awesome links to resources around Axway's Hyperloop for Titanium

**What is Hyperloop?**

Use any native API via JavaScript
Anything you can write in Objective-C, Swift, Java, or C# can be represented with JavaScript.

**What is this repo for?**

There's so much awesomeness about Hyperloop, but it's difficult to find an aggregated spot of up-to-date information about it.

This repo is an attempt to bridge that gap and link the community to relevant information so that we can make more badass software!

**Cool!  What can I do?**

- Got something that belongs here? [Fork](https://github.com/shouse/awesome-hyperloop-titanium/edit/master/README.md#fork-destination-box) and Submit a PR!
- Want information about something but don't have a link?  [Create an issue!](https://github.com/shouse/awesome-hyperloop-titanium/issues)

## Table of Contents (Suggest one)
 - [Information and Articles](https://github.com/shouse/awesome-hyperloop-titanium/blob/master/README.md#information-and-articles)
 - [Guides](https://github.com/shouse/awesome-hyperloop-titanium#guides)
 - [Modules](https://github.com/shouse/awesome-hyperloop-titanium#moduoles)
 - [Examples](https://github.com/shouse/awesome-hyperloop-titanium#examples) 

### Information and Articles
 - [Official homepage](https://github.com/appcelerator/hyperloop-examples)
 - [Axway Docs](https://docs.axway.com/bundle/Titanium_SDK_allOS_en/page/hyperloop.html) - Some of the best documentation currently
 - [Hyperloop FAQ](https://docs.axway.com/bundle/Titanium_SDK_allOS_en/page/hyperloop_faq.html)
 - [Medium.com](https://medium.com/all-titanium/titanium-an-introduction-to-hyperloop-by-hans-knoechel-47d4326ca52e) - Blog post by Rene Pot - Featuring Hans Knoechel.   At the TitaniumNL meetup in Amsterdam at February 3rd, Hans Knoechel talked about Hyperloop and what Hyperloop actually is.
In short, Hyperloop allows you to talk from Javascript straight to Objective-C/Swift or Java without having to write wrapper modules. This makes it really really easy to extend native API’s for Titanium.
The presentation has been recorded and can be seen in full on YouTube.
- [Developing Native APIs with Hyperloop](http://www.appcelerator.com/blog/2017/10/developing-native-apis-with-hyperloop-a-beginners-guide/) -  
By Erin Bailey
October 25, 2017: 
Intreview with Nazir Dogan, Mobile Application Developer and Software Developer at Etiya, has been using Hyperloop since its early days to create six unique open-sourced modules.

- [AppC Hyperloop Jira](https://jira.appcelerator.org/browse/TIMOB-25481?jql=project%20%3D%20TIMOB%20AND%20component%20%3D%20Hyperloop)
### Guides
[Enabling Hyperloop](https://wiki.appcelerator.org/display/guides2/Enabling+Hyperloop)
> Each Titanium project that want to use Hyperloop requires the Hyperloop-services to be enabled. By default, Hyperloop is disabled and you can enable it for your projects via the CLI or within Studio.

[AppC Blog - Tech Tutorial: Hyperloop Modules](http://www.appcelerator.com/blog/2017/07/tech-tutorial-hyperloop-modules/)

> In this in-depth video, Developer Evangelist Jason Kneen provides an overview of Titanium, its benefits and how it works. The tutorial delves into best practices for UI and views, navigation, buttons and labels, event handling, and data binding. Jason also demonstrates how these concepts are used in practice with a sample project code walkthrough.

**Android**

[Android Hyperloop Programming Guide](https://wiki.appcelerator.org/display/guides2/Android+Hyperloop+Programming+Guide) has information on running a demo application specifically for Android and you can learn how to use Hyperloop in your own project.

**iOS**

- [iOS Hyperloop Programming Guide](https://wiki.appcelerator.org/display/guides2/iOS+Hyperloop+Programming+Guide) has information on running a demo application specifically for iOS and you can learn how to use Hyperloop in your own project.
- [XIB](https://github.com/appcelerator/hyperloop-examples/blob/master/app/controllers/ios/xib.js) - Using Interface Builder via XIBs

**Windows**

[Windows Hyperloop Programming Guide](https://wiki.appcelerator.org/display/guides2/Windows+Hyperloop+Programming+Guide) has information on running a demo application specifically for Windows and you can learn how to use Hyperloop in your own project.

### Modules

- [Ti.mapbox](https://github.com/hyperloop-modules/ti.mapbox) - Use the MapBox SDK with Axway Hyperloop
- [Ti.hockeyapp](https://github.com/hyperloop-modules/ti.hockeyapp) - Hyperloop-based version of HockeyApp for both Android and iOS
- [Ti.speech](https://github.com/hyperloop-modules/ti.speech) - Use the iOS 10 SFSpeechRecognizer API in JavaScript with Appcelerator Hyperloop.
- [Ti.cloudsharing](https://github.com/hyperloop-modules/ti.cloudsharing) - Use the UICloudSharingController with Hyperloop in Titanium
- [Ti.snackbar](https://github.com/hyperloop-modules/ti.snackbar) - Use the Android Snackbar in Appcelerator Titanium.
- [Ti.reCAPTCHA](https://github.com/hansemannn/titanium-recaptcha) - Use the native reCAPTCHA API in Appcelerator Titanium (currently Android-only)
- [AppC Github Client](https://github.com/appcelerator-developer-relations/appc-github-client) - Dashboard used to monitor Github organizations, repositories and more!
- [Ti.Parallax](https://github.com/trkfabi/Ti.Parallax/blob/master/app/controllers/index.js) - Parallax effect with Titanium using Hyperloop. iOS only.
- [Ti.CalendarView](https://github.com/m1ga/Ti.CalendarView) - Axway Hyperloop Calendar View for Android
- [Ti.Firbase](https://github.com/hansemannn/titanium-firebase) - This project will contain all Firebase-related modules for Analytics, Cloud-Messaging, Authentication, Firestore etc.




- [Ti.MTTCircularSlider](https://github.com/nazrdogan/Ti.MTTCircularSlider) - Hyperloop module for https://github.com/MTT-IOS/MTTCircularSlider
- [Ti.FSCalendar](https://github.com/nazrdogan/Ti.FSCalendar) - Hyperloop module for https://github.com/WenchaoD/FSCalendar
- [Ti.DrawView](https://github.com/nazrdogan/Ti.DrawView) - Draw on your screen on iOS
- [Ti.IRLDocumentScanner](https://github.com/nazrdogan/Ti.IRLDocumentScanner) - Hyperloop module for https://github.com/charlymr/IRLDocumentScanner
- [Ti.HCSStarRatingView](https://github.com/nazrdogan/Ti.HCSStarRatingView) - Hyperloop module for https://github.com/hsousa/HCSStarRatingView

- [Ti.Firebase](https://github.com/loop-modules/Ti.Firebase) - Ti.Firebase is an iOS Hyperloop wrapper of the Firebase SDK.

- [Ti.UICollectionView](https://github.com/loop-modules/Ti.UICollectionView) - Ti.UICollectionView is an iOS Hyperloop wrapper of the native UICollectionView component.

- [Ti.EaIntroView](https://github.com/loop-modules/Ti.EaIntroView) - Ti.EaIntroView is an iOS Hyperloop wrapper of the EAIntroView library. Ti.EaIntroView provides a highly customizable solution for introduction views.

- [Ti.GoogleVR](https://github.com/loop-modules/Ti.GoogleVR) - Ti.GoogleVR is an iOS Hyperloop wrapper of the Google VR SDK. Ti.GoogleVR provides an easy way develop your own virtual reality experience using what Google best provides.

- [Ti.Estimote](https://github.com/loop-modules/Ti.Estimote) - Ti.Estimote is an iOS Hyperloop wrapper of the Estimote SDK.

- [Ti.Oauth](https://github.com/loop-modules/Ti.Oauth) - This HyperLoop module allows you to use the awesome OAuth.IO SDK for iOS.

- [Ti.Speech](https://github.com/loop-modules/Ti.Speech)
- [Ti.AndroidCharts](https://github.com/loop-modules/Ti.AndroidCharts.) - This HyperLoop module allows you to use highly customizable Charts with the MPAndroidChart library: https://github.com/PhilJay/MPAndroidChart. This module was originally posted on LoopModules: https://loopmodules.com/downloads/ti-androidcharts/
- [Ti.Reprint](https://github.com/loop-modules/Ti.Reprint) - This HyperLoop module allows you to implement fingerprint recognition in your Android app.
- [Ti.FAB](https://github.com/loop-modules/Ti.FAB) - Ti.FAB is an Android Hyperloop wrapper of the native Floating Action Button component. A Floating Action Button represents the primary action in an application.
- [Ti.WebView](https://github.com/loop-modules/Ti.WebView) - Ti.WebView is an iOS Hyperloop wrapper for two native iOS components: WKWebView, SFSafariViewController
- [Ti.Spinkit](https://github.com/loop-modules/Ti.Spinkit) - Ti.SpinKit is an iOS Hyperloop wrapper of the SpinKit-ObjC library.
- [Ti.AndroidViewAnimations](https://github.com/loop-modules/Ti.AndroidViewAnimations) - Ti.AndroidViewAnimations is an Android Hyperloop wrapper of the AndroidViewAnimations library. It provides a wide range of different animations that can be applied to your Titanium components.


### Code Examples
 - [Official Github example](https://github.com/appcelerator/hyperloop-examples) - Hyperloop Examples
>The following application demonstrates direct native API access using Appcelerator Hyperloop.
 - [Imaging Workshops ToDo](https://github.com/appcdev/imagine-workshops-todo/tree/hyperloop?files=1) - Todo Demo App
- [titanium-auth-session.js](https://gist.github.com/hansemannn/71b6181557ec0f6024e29c642dbe52e3) - Use Axway Hyperloop to perform OAuth-sessions with the iOS 11+ API "SFAuthenticationSession"



