THIS IS THE PHONEGAP IOS BRANCH

It is basically the exact copy of master (otherwise it needs to be rebased) + some Phonegap modified files + change done to support push notification plugin

To install:
- create a phonegap ios project (with phonegap create command)
- copy all the content of this rep into www.
- install the push notification plugin: https://github.com/mgcrea/cordova-push-notification (put the js file into the www)
- setup phonegap to allow different domain access + all necessary setup for push notification.

This version can be run in desktop if needed.