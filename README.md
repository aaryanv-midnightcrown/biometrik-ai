# Biometrik AI 🏋️‍♂️👁️

Client-side anthropometric vision analyzer and biomechanical workout engine.

## Overview
Biometrik AI combines real-time browser-based computer vision with a rule-based expert recommendation engine. It analyzes user structural geometry (V-Taper, shoulder symmetry) and strength matrix metrics to auto-compile personalized training plans without requiring paid APIs or third-party servers.

## Key Features
* **Normalized Anthropometrics:** Calculates geometric body proportions normalized against torso height to prevent camera-distance warping.
* **Client-Side Vision:** Powered by MediaPipe Pose for local processing (zero video data leaves the client device).
* **Deterministic Rule Engine:** Auto-detects strength imbalances and anatomical asymmetries to inject targeted accessory lifts into daily training splits.

## Stack
* **Frontend:** HTML5, CSS3, JavaScript ES6+
* **Vision Engine:** @mediapipe/pose via CDN
* **Deployment:** GitHub Pages / Static hosting