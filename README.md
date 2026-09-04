# Spatial Window

Mobile head-coupled 3D perspective prototype for the Samsung Galaxy S20 FE.

## What it does

- Three.js 3D scene with true off-axis projection
- Touch fallback for immediate testing
- DeviceOrientation / gyro fallback
- Front-camera face tracking with MediaPipe
- Head position drives the virtual camera so the phone behaves like a window into a 3D scene
- No backend and no API key

## Run

The full camera/sensor mode requires a secure context.

GitHub Pages is ideal because it serves the site over HTTPS.

After deployment open the Pages URL in Chrome on the Galaxy S20 FE, tap **Spatial starten**, allow the camera, then hold the phone still and move your head left/right.

## Privacy

Video from the front camera is processed locally in the browser. The demo does not upload camera frames to a server.

## External runtime dependencies

Loaded from public CDNs at runtime:

- Three.js
- MediaPipe Tasks Vision
- MediaPipe Face Landmarker model
