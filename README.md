
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
Flutter 3.13.7 • channel stable • https://github.com/flutter/flutter.git
Framework • revision 2f708eb839 (10 weeks ago) • 2023-10-09 09:58:08 -0500
Engine • revision a794cf2681
Tools • Dart 3.1.3 • DevTools 2.25.0
```
This means that Flutter is installed properly in your System

Execute another command to check whether all the requirements are met for development using flutter

```bash
flutter doctor -v
```
