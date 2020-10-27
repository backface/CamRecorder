# CamRecorder
A simple camera recorder that allows to record video clips (optionally with audio) in desktop and mobile browsers.

Migrated to an ES6 module and added functionality(unattach...) from  Valentin Schmidt's [CamRecorder](https://github.com/59de44955ebd/CamRecorder)

For browsers without MediaRecorder API - like Safari for macOS and iOS - it uses an extended version of Satoshi Ueyama's [Javascript MotionJPEG/AVI Builder](http://ushiroad.com/mjpeg/) and (for optional audio support) a modified version of Matt Diamond's [Recorder.js](https://github.com/mattdiamond/Recorderjs) to record to AVI. 

Copyright (c) 2020 Valentin Schmidt







