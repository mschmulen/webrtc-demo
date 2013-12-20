#WebRTC Mobile Demo

Leverages:

IOS client Application Libraries from:
  https://github.com/newOcean/webrtc-ios
  https://github.com/gandg/webrtc-ios
  https://code.google.com/p/webrtc/

Google:
  libjingle

Currently leveraging the Google Stun Server http://stun.l.google.com/ ( http://stun.l.google.com:19302/ ) for NAT traversal. 

##Instructions

To Run the demo
1. Compile the ios Application and install on device
1. open a web browser to http://apprtc.appspot.com
1. Enter the room number from the apprtc STUN server in the mobile client
1. The connection takes a few seconds.


##Supporting Links and demos and Notes

Open chrome://webrtc-internals/ in Chrome for webrtc logs

http://webrtc.googlecode.com/svn/trunk/samples/js/demos/html/pc1.html
https://apprtc.appspot.com/?r=48263249&debug=loopback
http://ninjanetic.com/how-to-get-started-with-webrtc-and-ios-without-wasting-10-hours-of-your-life/

[Mozilla WebRTC overview](https://hacks.mozilla.org/2013/07/webrtc-and-the-ocean-of-acronyms/)

[Android Demo](https://github.com/lapmore/AppRTCDemo)