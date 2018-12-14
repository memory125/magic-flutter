# magic-flutter
This repo focuses on flutter learning.

# Setup Development Environment
The development environment includes
  * Windows
  * Mac
  
  ## Windows
  * System Requirements
    * OS: Windows 7 SP1 or later (64-bit)
    * Disk: > 400 MB (does not include disk space for IDE/tools)
    * Tools: Flutter depends on these tools being available in your environment.
      * [Windows PowerShell 5.0](https://docs.microsoft.com/en-us/powershell/scripting/setup/installing-windows-powershell) or newer (this is pre-installed with Windows 10)
      * [Git for Windows](https://git-scm.com/download/win), with the Use Git from the Windows Command Prompt option.
      
  * Flutter SDK
    * Download [Flutter SDK 1.0](https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.0.0-stable.zip).
    * Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (eg. `C:\src\flutter`; do not install Flutter in a directory like `C:\Program Files\' that requires elevated privileges). 
    * Locate the file `flutter_console.bat` inside the flutter directory. Start it by double-clicking.
    * Add the full path to `flutter\bin` using to `PATH`under User variable.
    * After above operation completed, open power shell or cmd to run the following command.
      ```
      flutter doctor
      ```
      to see if there are any platform dependencies you need to complete the setup.
      
  * Android Studio
    * Download & Install [Android Studio](https://developer.android.com/studio/).
    
  ## Mac
  * System requirements
    * OS: macOS (64-bit)
    * Disk: > 700 MB (does not include disk space for IDE/tools).
    * Tools: Flutter depends on these command-line tools being available in your environment.
        ```
        bash, mkdir, rm, git, curl, unzip, which
        ```
        
  * Flutter SDK
    * Download [Flutter SDK 1.0](https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_v1.0.0-stable.zip).
    * Extract the file in the desired location, for example:
      ```
      cd ~/project
      unzip ~/Downloads/flutter_macos_v1.0.0-stable.zip
      ```
    * Add the `flutter` tool to your path.
     ```
     export PATH=$PATH:`pwd`/flutter/bin
     ```
    * After above operation completed, open terminal to run the following command.
      ```
      flutter doctor
      ```
      to see if there are any platform dependencies you need to complete the setup.
      
  * XCode
    * Install the latest XCode from [Apple Website](https://developer.apple.com/xcode/) or [Mac App Store](https://itunes.apple.com/us/app/xcode/id497799835).
    * Configure the Xcode command-line tools to use the newly-installed version of Xcode by running the following from the command line.
      ```
      sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
      ```
    * Make sure the Xcode license agreement is signed by either opening Xcode once and confirming or running `sudo xcodebuild -license` from the command line.
    
  * iOS Simulator
    * On your Mac, find the Simulator via Spotlight or by using the following command.
      ```
      open -a Simulator
      ```
    * Make sure your simulator is using a 64-bit device (iPhone 5s or later) by checking the settings in the simulator’s `Hardware > Device menu`.
    * Depending on your development machine’s screen size, simulated high-screen-density iOS devices may overflow your screen. Set the device scale under the `Window > Scale` menu in the simulator.
    * Start your app by running `flutter run`.  
  
  * Android Emulator
    * Install [Android Studio](https://developer.android.com/studio).
    * Start Android Studio, and go through the `Android Studio Setup Wizard`. This installs the latest Android SDK, Android SDK Platform-Tools, and Android SDK Build-Tools, which are required by Flutter when developing for Android.
    * Enable [VM acceleration](https://developer.android.com/studio/run/emulator-acceleration) on your machine.
    * Launch `Android Studio > Tools > Android > AVD Manager` and select `Create Virtual Device`. (The `Android` submenu is only present when inside an Android project.)
    * Choose a device definition and select `Next`.
    * Select one or more system images for the Android versions you want to emulate, and select `Next`. An x86 or x86_64 image is recommended.
    * Under Emulated Performance, select `Hardware - GLES 2.0` to enable [hardware acceleration](https://developer.android.com/studio/run/emulator-acceleration).
    * Verify the AVD configuration is correct, and select `Finish`.
    * In `Android Virtual Device Manager`, click `Run` in the toolbar. The emulator starts up and displays the default canvas for your selected OS version and device.
    
# Create Project
We can create flutter projects via the following command.
 ```
 flutter create project_name
 ```
 
# Hello Flutter
* The 1st and simple flutter sample to get started to learn flutter.

# References
* [Flutter Web](https://flutter.io/).
* [Flutter Installation On Windows](https://flutter.io/docs/get-started/install/windows).
* [Flutter Installation On Mac](https://flutter.io/docs/get-started/install/macos).
* [Flutter Chinese Resources](https://flutter-io.cn/).
* [Android Studio Web](https://developer.android.com/studio).
* [Android Studio Chinese Community](http://www.android-studio.org/index.php).
* [Android Managing AVDs](https://developer.android.com/studio/run/managing-avds).
