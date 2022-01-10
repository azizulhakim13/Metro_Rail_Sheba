# 1. Clone the Repository from github
Clone this repository with the command below:
```
git clone https://github.com/cse-250-2018/G62-Metro-Rail-Sheba.git
```
# 2. Install and Set Up Android Studio
Android Studio offers the quickest tools for developing apps for every Android device. We used Android Studio to program, compile, and execute the Metro Rail Sheba App. To use our application, we must first install and configure Android Studio. [This link](https://github.com/cse-250-2018/G62-Metro-Rail-Sheba.git) will take you to a step-by-step instruction on how to install and configure Android Studio.
***
Now Open Android Studio and navigate to the Metro Rail Sheba folder you cloned from the github repository. How to Open a Folder After you've arrived at the Android Studio's main page, choose the following path to keep moving :
```
Tap on File >> Open >> Cloned Folder >> Ok
```
Following that, you will be prompted to the folder on Android studio and and your screen should look like this:
![1](https://user-images.githubusercontent.com/52504999/148011722-a7c9d23b-15d1-418b-8fba-538dd7adb679.PNG)
***
# 3. Add and Sync your Firebase Account
Before you can add Firebase to your Android app, you need to create a Firebase project to connect to your Android app. 

**Step 1:** Create a Firebase project

1. In the Firebase console, click Add project.
2. If prompted, review and accept the Firebase terms.
3. Click Continue.
4. Click Create project
***

**Step 2:** Register your app with Firebase

1. Go to the Firebase console.
2. click the Android icon.
3. Enter your app's package name in the Android package name field.
4. Click Register app.
***

**Step 3:** Add a Firebase configuration file

1. Add the Firebase Android configuration file to your app:
   - Click Download google-services.json to obtain your Firebase Android config file (google-services.json).
   - Move your config file into the module (app-level) directory of your app.

2. Enable Firebase products in your app, add the google-services plugin to your Gradle files.
   - In your root-level (project-level) Gradle file (build.gradle), add rules to include the Google Services Gradle plugin. Check that you have Google's Maven repository, as well.
   - In your module (app-level) Gradle file (usually app/build.gradle), apply the Google Services Gradle plugin.
***  

**Step 4:** Add Firebase SDKs to your app
1. Using the Firebase Android BoM, declare the dependencies for the Firebase products that you want to use in your app. Declare them in your module (app-level) Gradle file (usually app/build.gradle).
2. Sync your app to ensure that all dependencies have the necessary versions.
***

**You may learn how to link Firebase with an Android app by watching [this video](https://www.youtube.com/watch?v=WsOt-3eNqz0).**

# 4. Finally!, Run
Finally if you have followed the way described above then you are all set to initiate the Application. Now there are two ways to run the application: using AVD and using real device. AVD needs some memory and sometimes causes laggings/errors. So Here I'm Showing the way of running the app on a Real Device.

**To Run the App on a Real Device Follow the steps:**
Set up your device as follows:
1. Connect your device to your development machine with a USB cable. If you developed on Windows, you might need to install the appropriate USB driver for your device.
2. Perform the following steps to enable USB debugging in the Developer options window:
   - Open the Settings app.
   - If your device uses Android v8.0 or higher, select System. Otherwise, proceed to the next step.
   - Scroll to the bottom and select About phone.
   - Scroll to the bottom and tap Build number seven times.
   - Return to the previous screen, scroll to the bottom, and tap Developer options.
   - In the Developer options window, scroll down to find and enable USB debugging.
***

Run the app on your device as follows:
1. In Android Studio, select your app from the run/debug configurations drop-down menu in the toolbar.
2. In the toolbar, select the device that you want to run your app on from the target device drop-down menu. See the image below:

![Screenshot (1)](https://user-images.githubusercontent.com/52504999/148020450-dc05a17b-44e9-4939-b871-f21dbfd59549.png)
***

**Click Run :**
Android Studio installs your app on your connected device and starts it. You can now see and check The UI and Functionalities of Metro Raile Sheba APP.

![4](https://user-images.githubusercontent.com/52504999/148041622-d73b7ed7-fb7e-4a89-b8b2-6e7264c3d206.jpg)
*** 

To proceed from home page to other functionalities check [here](https://github.com/cse-250-2018/G62-Metro-Rail-Sheba/blob/main/description.md)to find the way.
