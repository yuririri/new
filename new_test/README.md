

# real



## Usage



## Developing



### Tools

Created with [Nodeclipse](https://github.com/Nodeclipse/nodeclipse-1)
 ([Eclipse Marketplace](http://marketplace.eclipse.org/content/nodeclipse), [site](http://www.nodeclipse.org))   

Nodeclipse is free open-source project that grows with your contributions.


video_call_with_chat.html
This is a basic web page that connects a Caller and a Callee via a Web Socket signaling server to support a video call and text based chat.
This also includes:
- webrtc_polyfill.js
This is a simple WebRTC polyfill designed to make it easy to write WebRTC code that runs on different browser implementations (e.g. Chrome, Firefox, etc.).

webrtc_signal_server.js
This is a node.js based script that provides Web server and Web Socket server functionality required to support the example html based WebRTC applications.
This requires the "websocket" package that can be installed from the command line by typing "npm install websocket".
To start this server from the command line simply type "node basic_signal_server.js" then point your browser at http://localhost:1234
You can replace localhost with any ip address you like and you can replace 1234 with any port you like too.
NOTE: It is important that the ip address you use here is also accessible by the other person you want to join your call.

