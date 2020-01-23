# Ionic Workspace

## Cordova setup
Install ionic, native-run and cordova-res globally: `npm i -g ionic cordova-res native-run`

Then prepare cordova : `ionic cordova platform add ios android && ionic cordova prepare`

Run android live-reload: `ionic cordova run android -l`

Check the chrome dev tools error about the missing `cordova.js` file.