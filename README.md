<h1>Project Name</h1>

<h2>Requirements</h2>
<ul>
  <li>Node.js 15+</li>
  <li>Xcode (for iOS development)</li>
  <li>CocoaPods (for managing iOS dependencies)</li>
  <li>Android Studio (for Android development)</li>
</ul>
<br>
<h2>Starting from Scratch</h2>
<ol>
  <li><strong>Create the project</strong>
    <pre><code>npx @react-native-community/cli init</code>;
  </li>
  <br>
   <li><strong>Install React Native WebView:</strong>
    <pre><code>npm install react-native-webview</code></pre>
  </li>
  <br>
  <li><strong>Install dependencies:</strong>
    <pre><code>npm install</code></pre>
  </li>
  <br>
  <li><strong>Configure iOS and Android folders:</strong>
    <ul>
      <li><strong>iOS:</strong> Make sure you have Xcode installed. Navigate to the iOS directory and run:
        <pre><code>cd ios
pod install
cd ..</code></pre>
      </li>
      <li><strong>Android:</strong> Make sure Android Studio is installed and set up.</li>
    </ul>
  </li>
  <br>
  <li><strong>Start the Project:</strong>
    <ul>
      <li>For iOS:
        <pre><code>npx react-native run-ios</code></pre>
      </li>
      <li>For Android:
        <pre><code>npx react-native run-android</code></pre>
      </li>
    </ul>
  </li>
  <br>
  <li><strong>Change <code>App.tsx</code>:</strong> Modify the <code>App.tsx</code> file as needed for your project setup.</li>
</ol>
<br>
<h2>Cloning the Project</h2>
<ol>
  <li><strong>Clone the repository:</strong>
    <pre><code>git clone https://github.com/ThiagoMarvinSoares/WebView-react-native.git&gt;
cd &lt;project-directory&gt;</code></pre>
  </li>
  
  <li><strong>Install dependencies:</strong>
    <pre><code>npm install</code></pre>
  </li>
  <br>
  <li><strong>Verify setup:</strong>
    <pre><code>npx react-native doctor</code></pre>
  </li>
  <br>
  <li><strong>Start the React Native server:</strong>
    <pre><code>npx react-native start</code></pre>
  </li>
  <br>
  <li><strong>Platform-Specific Setup:</strong>
    <ul>
      <li><strong>iOS:</strong>
        <ul>
          <li>Make sure you have Xcode installed.</li>
          <li>Navigate to the iOS directory and install CocoaPods:
            <pre><code>cd ios
pod install
cd ..</code></pre>
          </li>
          <li>Run the project:
            <pre><code>npx react-native run-ios</code></pre>
          </li>
        </ul>
      </li>
      <li><strong>Android:</strong>
        <ul>
          <li>Make sure Android Studio is installed and properly configured.</li>
          <li>Run the project:
            <pre><code>npx react-native run-android</code></pre>
          </li>
        </ul>
      </li>
    </ul>
  </li>
</ol>
<br>
<h2>Common errors</h2>
      <p>Remember to run <code>npx react-native doctor</code> to check any necessary needed configuration</p>
      <li><strong>Android_HOME will need to be setup:</strong>
        <p>In terminal</p>
        <ul>
          <li>
            <code>
            <pre>export ANDROID_HOME={YOUR_PATH}<br></pre>
            <pre>export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools</pre>
            </code></li><br>
            <pre><code></code></pre>
          </li>
        </ul>
      </li>
