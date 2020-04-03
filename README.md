# WebRTC Videochat 
This simple app demonstrates the use use of WebRTC. It allows the communication between Android and iOS devices.

## Prerequisites
You need to create a Firebase project and add the `google-services.json` file to the app directory.

## Running the project
Once you have installed all the dependencies, you can run the project. 

Keep in mind that there's no support for background functionality. The app only works on foreground. 

## Credits
The signaling part of the app is based on the [Firebase + WebRTC Codelab](https://webrtc.org/getting-started/firebase-rtc-codelab), which is a great intro into WebRTC.

This project uses the compiled version of WebRTC that can be found [here.](https://bintray.com/google/webrtc/google-webrtc/1.0.30039#read) 

The WebRTCClient is based on the [SwiftyWebRTC project](https://github.com/Ankit-Aggarwal/SwiftyWebRTC). They have done a great job creating a wrapper that works on Swift. [Check it out](https://hackernoon.com/swiftywebrtc-789936b0e39b) 
