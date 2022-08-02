# wda-app-experiments
A Collection of wda apps that should exist. What is a wda? Web Driven Application they get created using the browser devtools protocol that is widly implemented and can also use extended webdrivers to support legacy ore none devtools protocol browsers. 

to speed up wda creation we use 
```
npm i @stealify/desktop 
```

it exports a global installed api with a local chromium install bundled. If you install this package many times it will always install and use a single version of chromium bundled with it. unless you use special magic to avoid that but then you would not use and install that package.

## App List

### Desktop Screen Sharing

### image Editor
experiment take squoosh 

### make websites viewable & printable offline
There are many methods for that we need to explore usefull once as there is most time parts that need stripping and adjustment. 

### Collect Data 
A application that takes selectors and small app code to collect and stringify data from multiple sources. 

### Video Composition and Directly Stream to twitch
Using WebRTC and DirectSockets in a mix with ffmpeg (maybe wasm) it would be nice if some one would reverse engineer the rtmp protocol implementation of ffmpeg to get a twitch compatible directSockets implementation done for streaming.

### Virtual Audio Cabel and Manager
Use the Audio API's and WebRTC to offer virtual audio cabels and such stuff cross platform. 

## Tooling List

### Installer
something like open-pwa but more major we need concepts to install stuff

### Installer Tooling
Create Icons and all the stuff that electron does. 

### App Scheduler something like cron. 
