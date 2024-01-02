
# Flutter Setup Without Android Studio

Extract Folders from Android_Flutter.zip

Move the **android-sdk** and **flutter** Folder to **C** drive

![App Screenshot](https://raw.githubusercontent.com/Jenihacker/images/main/Screenshot%202024-01-02%20203338.png)

**Note:** This method only works if the **android-sdk** and **flutter** folder are kept in the **C** drive. Please dont keep it in **seperate folder** or **seperate drive**

After this execute the **installation.bat** script by **right clicking** on the file and **Run as Administrator**

This opens up a **command prompt** window which opens up another **two** windows.

Accept all **Terms and conditions** by entering **y** and after the acceptance close the window.

This completes the installation process.

Open a **command prompt** and then execute the following command

```bash
  flutter doctor -v
```

This would give the following output:

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

Checking Android licenses is taking an unexpectedl                                                  
[√] Android toolchain - develop for Android
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

**Flutter**, **Windows Version**, **Android toolchain**, **Chrome**, **VS Code**, **Connected device**, **Network resources** should have **[√]** mark.

This is enough to start Flutter Android Development.

