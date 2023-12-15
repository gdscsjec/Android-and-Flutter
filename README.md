
# Flutter and Android Studio Installation

Here are the steps:

Download and install Visual Studio Community


After Installation select Mobile development with C++ for Installation 


[Visual Studio Community](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&passive=false&cid=2030)

![App Screenshot](https://raw.githubusercontent.com/Jenihacker/images/main/WhatsApp%20Image%202023-12-14%20at%2021.53.44_06b12dc5.jpg)

Download and Install Android Studio from below link

[Android Studio](https://developer.android.com/studio?gclid=Cj0KCQiAj_CrBhD-ARIsAIiMxT9EZqd-7aL8h4Y2kp2Sh3ZBvaW48Vv4upvU31LZ6amp3Nj_NKsz7p0aAhcjEALw_wcB&gclsrc=aw.ds)

Download Flutter from below link

[Flutter 3.13.0](https://www.filehorse.com/download-flutter/82264/download/)

Open **This PC** and open **C drive**

Extract the flutter zip folder in **C drive** which creates a folder **flutter**

Open the folder **flutter** and open **bin** folder

Click on **start** button and type **env** and press enter

This open up the following window

![App Screenshot](https://raw.githubusercontent.com/Jenihacker/images/main/Screenshot%202023-12-15%20145628.png)

Click on **Environment Variables** Button

![App Screenshot](https://raw.githubusercontent.com/Jenihacker/images/main/Screenshot%202023-12-15%20145909.png)

Double click on **Path** in System Variables and which opens up another window

Click on New and Paste the path:

**C:\flutter\bin**

and click **OK**

Open Command Prompt and type the following commands to ensure flutter is installed:


```bash
  flutter --version
```

This prints the message as follows:

```bash
Flutter 3.13.0 • channel stable •
https://github.com/flutter/flutter.git
Framework • revision efbf63d9c6 (4 months ago) •
2023-08-15 21:05:06 -0500
Engine • revision 1ac611c64e
Tools • Dart 3.1.0 • DevTools 2.25.0
```
This means that Flutter is installed properly in your System

Execute another command to check whether all the requirements are met for development using flutter

```bash
flutter doctor -v
```

This prints out the following message:
```bash
[√] Flutter (Channel stable, 3.13.0, on Microsoft
    Windows [Version 10.0.22621.2861], locale
    en-US)
    • Flutter version 3.13.0 on channel stable at
      C:\src\flutter
    • Upstream repository
      https://github.com/flutter/flutter.git
    • Framework revision efbf63d9c6 (4 months
      ago), 2023-08-15 21:05:06 -0500
    • Engine revision 1ac611c64e
    • Dart version 3.1.0
    • DevTools version 2.25.0

[√] Windows Version (Installed version of Windows
    is version 10 or higher)

Checking Android licenses is taking an unexpectedl                                                  [√] Android toolchain - develop for Android
    devices (Android SDK version 33.0.2)
    • Android SDK at
      C:\Users\asvij\AppData\Local\Android\sdk
    • Platform android-34, build-tools 33.0.2
    • Java binary at: C:\Program
      Files\Android\Android Studio\jbr\bin\java   
    • Java version OpenJDK Runtime Environment    
      (build 17.0.6+0-b2043.56-10027231)
    • All Android licenses accepted.

[√] Chrome - develop for the web
    • Chrome at C:\Program
      Files\Google\Chrome\Application\chrome.exe  

[√] Visual Studio - develop Windows apps (Visual  
    Studio Community 2022 17.5.4)
    • Visual Studio at C:\Program Files\Microsoft 
      Visual Studio\2022\Community
    • Visual Studio Community 2022 version        
      17.5.33530.505
    • Windows 10 SDK version 10.0.22000.0

[√] Android Studio (version 2022.3)
    • Android Studio at C:\Program
      Files\Android\Android Studio
    • Flutter plugin can be installed from:       
      
      https://plugins.jetbrains.com/plugin/9212-fl
      utter
    • Dart plugin can be installed from:
      
      https://plugins.jetbrains.com/plugin/6351-da
      rt
    • Java version OpenJDK Runtime Environment    
      (build 17.0.6+0-b2043.56-10027231)

[√] VS Code (version 1.85.1)
    • VS Code at
      C:\Users\asvij\AppData\Local\Programs\Micros
      oft VS Code
    • Flutter extension version 3.78.0

[√] Connected device (3 available)
    • Windows (desktop) • windows • windows-x64   
      • Microsoft Windows [Version
      10.0.22621.2861]
    • Chrome (web)      • chrome  • web-javascript
      • Google Chrome 120.0.6099.71
    • Edge (web)        • edge    • web-javascript
      • Microsoft Edge 120.0.2210.61

[√] Network resources
    • All expected network resources are
      available.

• No issues found!
```
