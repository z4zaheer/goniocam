# GonioCam

Camera goniometer in a single HTML file. It measures joint angles from the live camera feed using [MediaPipe Pose Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker), which runs entirely on the device.

**Current stage:** step 1, which covers the camera, the landmark overlay for the selected limb, and knee flexion (left/right) with smoothing and a visibility gate.

## Use

Open `index.html` over **https** or `localhost`, for example through GitHub Pages. Browsers block camera access on `file://`. An internet connection is needed on first load to fetch the MediaPipe library (jsDelivr) and the pose model (Google Storage).

## Privacy

All processing happens in the browser. Nothing is uploaded or stored.

> Screening and demo tool. Not a validated replacement for a universal goniometer.
