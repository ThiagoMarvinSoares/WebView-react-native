<h1>WebView App - React Native</h1><br>
This is a simple mobile application developed using React Native that displays a WebView to render web content. The app is compatible with both Android and iOS platforms and can be compiled using Android Studio for Android and Xcode for iOS.<br>

<h2>Getting Started</h2>
 Run npx create-react-app
<h2>Features</h2><br>
Displays a WebView that loads web content from a URL.<br>
Cross-platform support for both Android and iOS.<br>
Easy to compile and run on emulators or real devices.<br>

<h2>Prerequisites</h2><br>
Before running or compiling the application, ensure you have the following installed:<br>

<h3>General</h3><br>
Node.js (v12.x or higher)<br>
npm or yarn<br>
React Native CLI (globally installed)<br>
React Native WebView package (react-native-webview)<br>

<h3>For Android</h3><br>
Android Studio with Android SDK installed.<br>
Java Development Kit (JDK) 11.<br>
Android Emulator or a physical Android device for testing.<br>

<h3>For iOS</h3><br>
Xcode (latest version).<br>
A physical iOS device or iOS Simulator.<br>
Cocoapods (for iOS dependencies).<br>

<h2>Errors with Android Studio?</h2><br>
Run <code>npx react-native doctor</code> to check for the status of dependencies.<br>
Run <code>npx react-native start</code> to run the development server.<br>
Check these links for troubleshooting, they might help:<br>
```Cannot set ANDROID_HOME```: <a href="https://stackoverflow.com/questions/36778085/unable-to-build-react-native-app-on-android-device-failed-to-find-target-with-h/36787719#36787719">Here</a><br>

<h3>Android Studio uses port 8081 by default</h3><br>
If Android Studio is using port 8081 (which is also the port used by React Native’s Metro Bundler), you might run into issues. Here are a few ways to resolve this:<br>

1. **Stop any existing processes using port 8081**:<br>
    You can check which process is using port 8081 and stop it.<br>
    On Linux/macOS, run:<br>
    ```bash
    sudo lsof -i :8081
    sudo kill -9 <PID>
    ```<br>
    On Windows, run:<br>
    ```cmd
    netstat -aon | findstr :8081
    taskkill /PID <PID> /F
    ```<br>

2. **Change the Metro Bundler port**:<br>
   I didn't find a way to correcly change the port, when I tried to in android studio it just refused to.

Let me know if you need any further assistance!
