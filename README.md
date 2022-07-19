# Description

A simple project which intended purpose is to interface with the native messaging connectNative protocol. Thus enabling messaging between chrome extensions and your node application.


# Setup

1. Configure your `com.google.chrome.example.echo-win.json` to your chrome extension, by changing the `allowed_origins` field. You may require to alter the `./native-messaging.bat` file to represent your OS.
2. Once your OS has registered the path of the `com.google.chrome.example.echo-win.json`, run your extension, triggering the `connectNative` method in the `chrome.runtime` API. 
3. If setup correctly the node process should launch and messaging through connectNative enabled. 
