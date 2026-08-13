# 🏎️ Virtual Steering Wheel Using Hand Tracking

A computer-vision-based virtual steering wheel that allows users to control racing games using hand gestures instead of a physical keyboard or steering wheel.

The project uses **OpenCV** for camera processing, **MediaPipe Hands** for real-time hand tracking, and **Pynput** to simulate keyboard inputs.

---

## 🚀 Features

- 🖐️ Real-time two-hand detection
- 🎮 Virtual steering wheel using hand position
- ⬅️ Tilt hands left to steer left
- ➡️ Tilt hands right to steer right
- 🏎️ Both hands closed → Accelerate
- 🛑 Both hands open → Brake
- 🎯 Dead-zone based steering control
- 📊 Real-time steering angle display
- 📈 Steering strength indicator
- ⚡ Real-time FPS display
- 🎨 Visual HUD interface
- 🔄 Automatic camera mirroring
- ⌨️ Simulated keyboard controls
- 🛡️ Automatic keyboard-key release when hands disappear
- ⚙️ Optimized for real-time performance

---

## 🧠 How It Works

The application captures video from the webcam and detects both hands using MediaPipe.

The wrist position of the left and right hands is used to calculate the angle between them.

```text
        Left Hand
            ●
             \
              \
               ● Right Hand
