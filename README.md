# FlutterShopApp

Learning to build an E-Commerce Flutter application from scratch following Maximilian Schwarzmüller's (Academind) tutorial on Udemy **Flutter & Dart - The Complete Guide [2020 Edition]**.

Had to redo from scratch as I forgot most of the core concepts after 2 months not working on it.

# Pros and Cons (based on my experience so far)
- Widget tree structure makes the code vertically long and such a hassle to scroll through and understand (as Dart is not a commonly used language and I feel its more akin to structured language like Java compared to Javascript)
- Running an Android emulation is a VERY RESOURCE HUNGRY AND TEDIOUS PROCESS. The slowness of it during operation makes me avoid using it in conjunction with Dart DevTools.
- Compared to Web Dev. You'd have to be a lot more meticulous as people generally have less patience on an app compared to web apps (eg: Waiting on promises) and app relies a lot more on UI elements to guide user behaviour.
- Its been often quoted to be a good framework to quickly prototype an app without much hassle. I have no idea as I've never extensively coded on native language for apps. Probably will use it for hackathons if we're going with an app idea. But then again, how many developers would know how to code on Flutter?
- Tons of classes and enums makes building apps from scratch easy....if you know what you're looking for. My guess is that the more time I spend on actually using Flutter and delving into the docs in real world projects, the faster I get to know what goes where its needed. Much like how some common CSS attributes and Bootstrap classes are now second nature to me from just muscle memory.

**Total Hours Required : 41.5**

# Progress on completed sections
- ✅ Section 1 : Introduction
- ✅ Section 2 : Flutter Basics [QUIZ APP]
- ✅ Section 3 : Running Apps on Different Devices & Debugging Apps
- ✅ Section 4 : Widgets, Styling, Adding Logic - Building a Real App [PERSONAL EXPENSES APP]
- ✅ Section 5 : Responsive & Adaptive User Interfaces and Apps
- ✅ Section 6 : Widget & Flutter Internals - Deep Dive
- ✅ Section 7 : Navigation & Multiple Screens [MEALS APP]
- ✅ Section 8 : State Management [SHOP APP]
- ✅ Section 9 : Working with User Input & Forms [SHOP APP]
- ✅ Section 10 : Sending Http Requests [SHOP APP]
- ✅ Section 11 : Adding User Authentication [SHOP APP]
- ✅ Section 12 : Adding Animations [SHOP APP]
- Section 13 : Using Native Device Features (Camera, Maps, Location, ...) [GREAT PLACES APP]
- Section 14 : Firebase, Image Upload, Push Notifications - Building a Chat App
- Section 15 : Running Native Swift, ObjectiveC, Java or Kotlin Code
- Section 16 : Publishing to the App Stores
- Section 17 : Roundup & Next Steps
- Section 18 : Roundup

# Key Takeaways:
## 03/01/2021

### Important Basics
- Everything is a widget
- Stateless vs Stateful Widgets (setState())
- Dart DevTools
- Columns and Rows. Main Axis Alignment and Cross Axis Alignment
- TextEditingController

### UI and Stylings
- MediaQuery.of(context) | Paddings | Flexible | BoxDecorations
- SingleChildScrollView | ViewBuilder
- AppBar buttons | Modal Bottom Sheet | showDialog
- Theme.of(context)

### Flutter Architecture
- Widget lifecycle
- Screen rebuild
- Breaking widgets into smaller widgets as separation of concerns
- Builder functions for widgets

### Core advanced concepts
- Routing
- Navigation.of(context)pop/push/pushNamed
- Passing data by routes / Passing data by Constructor
- onGenerateRoute / onUnknownRoute
- Tabs and Drawers
- State Management (Provider & Consumer)
- Local vs App Wide States (Stateful Widgets vs Providers)
- Using Firebase as a main database
- async await vs try catch Futures
- REST API using Firebase
- Optimistic Updating
- Firebase Authentication using Tokens
- ChangeNotifierProvider & ChangeNotifierProxyProvider

### Advanced Animation concepts
- Manual animations
- AnimatedBuilder
- AnimatedContainer
- AnimatedController, Animated<Size>, Animated<Offset>, Tween<Size>, Tween<Offset>
- CurvedAnimation
- FadeInImage
- Hero transitions
- CustomScrollView, SliverAppBar, SliverList, SliverChildListDelegate
- CustomRoute, MaterialPageRoute, buildTransitions, PageTransitionsBuilder

### Using Device Features
- import dart:io
- File datatype
- Image.file
- ImagePicker package. ImagePicker.getImage, ImageSource
- Added Path and PathProvider packages
- sqflite, getDatabasesPath, openDatabase