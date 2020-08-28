# SIP.js

This repository forked from onsip/SIP.js v0.15.10
I use node-webrtc/node-webrtc and websockets/ws instead of native ws rtc api on browser.
So it can run on nodejs env.

## Download

* npm: `npm install git:https://github.com/Winston87245/SIP.js.git#node-environment`

## How to use

If you want to play audio on call.
Take tylerlong/node-webrtc-audio-stream-source as a reference

see ./example/PlayAudio.js

## Note
Confirm your audio file codec is supported.

## License
MIT
