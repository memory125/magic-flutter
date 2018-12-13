# magic-flutter
This repo focuses on flutter learning.

# Setup Development Environment
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
    
# Hello Flutter
* The 1st and simple flutter sample to get started to learn flutter.

# References
* [Flutter Web](https://flutter.io/).
* [Flutter Installation On Windows](https://flutter.io/docs/get-started/install/windows).
* [Flutter Chinese Resources](https://flutter-io.cn/).
* [Android Studio Chinese Community](http://www.android-studio.org/index.php).
