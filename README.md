# 🖥️ Smart Posture Monitor

The **Smart Posture Monitor** is a professional-grade web tool that utilizes artificial intelligence (convolutional neural networks via TensorFlow.js) to analyze your torso and facial geometry in real time. Its goal is to mitigate muscle fatigue and prevent lumbar or cervical injuries through immediate visual alerts when it detects that you are slouching.

---

### 🚀 Steps to Start Monitoring

1. **Hardware Connection:** Ensure your webcam (integrated or external USB) is properly connected to the computer before opening the application.
2. **Grant Permissions:** Upon loading the site, the web browser will request camera access. Click **"Allow"**. The system requires this permission exclusively to capture video locally.
3. **Select the Correct Device:** * Head over to the **"Select Video Device"** dropdown menu.
   * If you have more than one camera connected (for example, a laptop's integrated camera and an external webcam), ensure you choose the camera pointing directly at your workspace.
4. **Activation:** Click the **"Start Monitor Pro"** button. The system will take a couple of seconds to load the AI weights and cleanly synchronize the video.

---

### 💡 Best Practices for Use

To guarantee 100% detection effectiveness and avoid false positives, follow these environmental recommendations:

* **Framing and Distance:** Position the camera head-on or at a subtle diagonal angle. Your face, shoulders, and upper chest must be visible in the video box. Avoid having the camera point solely at your forehead or chin.
* **Lighting Conditions:** Work in a well-lit space. Light should ideally come from the front or the sides. If you are completely backlit (for example, with a bright window behind you), the AI might have difficulty recognizing your body silhouette.
* **Baseline Posture Calibration:** Upon clicking start, immediately sit in your ideal ergonomic posture (straight back, relaxed shoulders). This helps the algorithm validate your correct position from the very first second of analysis.
* **Clear Background:** Try to prevent other people from crossing in the background of the camera frame, as the model is optimized to analyze a single user at a time.

---

### ⚠️ Important Notices and Troubleshooting

* **On-the-fly camera changes:** If you decide to change the camera in the selector while the monitor is already active, you need to refresh the page (`F5` or `Cmd + R`) to cleanly release the previous hardware and start the new video stream.
* **Camera Busy:** If the interface displays a "Camera busy" error, verify that you do not have another application open in the background using the video feed (such as Zoom, Microsoft Teams, Slack, or Discord).
* **🔒 Absolute Privacy Note:** Your privacy is the absolute technical priority. This software **does not record, store, or transmit** images or video clips to any external server. The artificial intelligence processing runs 100% locally within your own web browser via your hardware (graphics card or processor).
