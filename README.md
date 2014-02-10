AndroidBootcampProject
======================

## Objectives
To teach Java programmers the basics of Android development using Agile best practices, by incrementally developing a small game over a period of six weeks.

## The App: Treasure Hunt
A single player game. The app supplies a list of photos of 'treasures' in your local area, with hints on how to find them. Your job is to run (or stroll) around the area to find each treasure and take a photo of it. Points are awarded according to how many treasures you can locate, how long you take, and how close you were to the original photo location.

## Pre-Bootcamp Preparation

Follow these setup steps before your first session:

1. Install [Java SE SDK 7](http://www.oracle.com/technetwork/java/javase/downloads/index.html) if you don't have it
1. Download and install [Android Studio](http://tools.android.com/download/studio/canary)
1. Studio will prompt you to create a new project. Use the default settings, except:
  1. Enter any project name you like
  1. Enter "HelloAndroid" as the Activity Name
  1. Enter activity_hello as the layout name
  1. Change the Package Name to com.thoughtworks.androidbootcamp or something that's relevant to you. Note that a device can carry only one application from any given package, and the Google Play store will only list one application per package.
  1. Select Navigation Type: Action Bar Spinner
1. If you previously had a version of Android installed on your machine, you may need to use Android's [SDK manager](http://developer.android.com/tools/help/sdk-manager.html) to install Build Tools v19.
1. (Optional) Download and install [Genymotion](https://cloud.genymotion.com/page/launchpad/download/)
  1. Create an account on the [Genymotion cloud](https://cloud.genymotion.com/page/customer/login/)
  1. (Mac only) Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  1. Download and install Genymotion and Genymotion Shell
  1. Install the Genymotion plugin for Android Studio:
    1. Android Studio > Preferences > Plugins
    1. Browse Repositories
    1. Search for Genymotion
    1. Choose Download and Install from the context menu
  1. Open the Genymotion app and create a new virtual device

The initial codebase looks [like this] (https://github.com/macosgrove/AndroidBootcampProject/tree/v0)

## Week 1: Hello Android
Goals: 
 * Develop a working "hello world" app and explore its anatomy.
 * Allow the user to enter their name.  
[View the Presentation](http://prezi.com/jibn_vzm9rml/?utm_campaign=share&utm_medium=copy)  
[Exercise 1: Explore the Lifecycle](https://github.com/macosgrove/AndroidBootcampProject/commit/bd381649f0981bc9d74b90af2389acc364f16914)  
[Exercise 2: Create a Second Activity Part 1](https://github.com/macosgrove/AndroidBootcampProject/commit/f794de4638037308e2100b5bf73043df89540231),
[Part 2](https://github.com/macosgrove/AndroidBootcampProject/commit/173f178c6a933500e047120ce2f94b8046d927a7)  
[Exercise 3: Capture the Player's Name](https://github.com/macosgrove/AndroidBootcampProject/commit/1716a164608a5710869d36562379d0203dfc2b64)  
[Exercise 4: Keep the game state safe](https://github.com/macosgrove/AndroidBootcampProject/commit/50e7ab9107659897a733298e2504c14578ba85c9),
[Optional extra](https://github.com/macosgrove/AndroidBootcampProject/commit/2059476941cedb19db271ee68140b844a7404998)  

## Week 2: BDD with Android
Goals: 
 * Add a framework for behaviour driven development including a unit test and a functional test
 * Allow the user to start and end a game.  
[View the Presentation](http://prezi.com/78y82u9ld2yy/?utm_campaign=share&utm_medium=copy)  
[Exercise 1: Create a failing instrument test](https://github.com/macosgrove/AndroidBootcampProject/commit/9f5d25952ac48d4e6c9ea5a0345c1ece2c43ddae)  
[Exercise 2: Add Espresso to the test Part 1](https://github.com/macosgrove/AndroidBootcampProject/commit/5d137c44445bdcc97bb02a53246a3fe6f44a1915),
[Part 2](https://github.com/macosgrove/AndroidBootcampProject/commit/6a10373f167e709c907797aa00953ee899bd8ed2)  
[Exercise 3: Some new behaviour](https://github.com/macosgrove/AndroidBootcampProject/commit/ff41e46f18da9ab904607f62a766368459b78db2)  
[Exercise 4: Add Unit Tests Part 1,](https://github.com/macosgrove/AndroidBootcampProject/commit/816cc9f7dc56a3d3d09b040891992d336f6bc277)
[Part 2,](https://github.com/macosgrove/AndroidBootcampProject/commit/527d923d5f9d0fe8072422b72c56ba01ee9e5d1c) 
[Part 3](https://github.com/macosgrove/AndroidBootcampProject/commit/0549ce579badab5c61b150f71b7bfd0faaf36243)  
[Step by step instructions](https://github.com/macosgrove/AndroidBootcampProject/blob/master/BDDinAS.md)  
[Exercise 5: Make the tests pass](https://github.com/macosgrove/AndroidBootcampProject/commit/9ef2627ff2e6e40b4d526ba604aadba9bbf128e9)  

## Week 3: Layout and Design
Goal: Display a list of Treasures (from a provided file)

## Week 4: Using the Hardware
Goal: Take a photo of a found Treasure. Evaluate its proximity to the listed Treasure

## Week 5: Data & Communication
Goal: Retrieve a real list of Treasures from a server

## Week 6: Google APIs
Goal: Complete the game with a map of actual vs found Treasure locations. Generate a score.

## Resources
### Android in General
[Android Developers site](http://developer.android.com/develop/index.html)  
[The Busy Coder's Guide to Android Development](http://commonsware.com/Android/)  
[Saving and retrieving instance state](http://www.intertech.com/Blog/saving-and-retrieving-android-instance-state-part-1/)  
[Parcelable vs Serializable](http://www.developerphil.com/parcelable-vs-serializable/)

###Genymotion
[Genymotion Users Guide](https://cloud.genymotion.com/page/doc/)
