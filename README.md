# YOLOv10-TFLite-on-Android-for-Object-Detection 🚀📱

A cutting-edge **Object Detection Application** built using the YOLOv10 model, optimized for mobile deployment with **TFLite**, and seamlessly integrated into an Android app. This project leverages the power of YOLOv10's high-speed and accurate object detection, bringing advanced computer vision capabilities to your pocket.

---

## ✨ Features

1. **Efficient YOLOv10 Model Integration**
   - The YOLOv10 model is converted into **TFLite** (TensorFlow Lite) format for lightweight deployment.
2. **Real-Time Object Detection**
   - Uses your phone's camera to identify and detect objects in real time.
3. **Mobile-Friendly Application**
   - Fully compatible with Android devices, offering smooth and responsive detection performance.
4. **Plug-and-Play Usage**
   - No complex setup required—simply download the APK, install, and detect!

---

# 🛠️ Setup and Installation
Prerequisites:
1. Android Studio installed on your system.
2. A smartphone running Android 5.0 (Lollipop) or above.
3. Basic understanding of Android development (optional).

## Steps
1. Clone this Repository
```plaintext
git clone https://github.com/yourusername/YOLOv10-TFLite-on-Android-for-Object-Detection.git
cd YOLOv10-TFLite-on-Android-for-Object-Detection
```
2. Make sure to run the colab file and export the YOLOv10-LiteRT model
3. Ensure the LiteRT model is placed in the [assets](https://github.com/atharvakulkarni-07/YOLOv10-TFLite-Android/tree/main/Android_App/app/src/main/assets) folder, which is a subfolder of Andriod application
4. Open the [app](https://github.com/atharvakulkarni-07/YOLOv10-TFLite-Android/tree/main/Android_App/app) folder in Android Studio
5. Launch Android Studio and open it as a new project.
6. Ensure the YOLOv10 TFLite model is in the assets folder
7. Build the App
8. Sync the project and build the APK.
9. Get the APK in your android device (via USB / other methods)
10. Install the APK and Run the App

# 📸 How It Works
1. Open the app on your Android device.
2. Grant camera permissions if prompted.
3. Point your camera at an object.
4. The app will identify the object and display its label and bounding box in real time.
   
# 💻 Technical Details
1. YOLOv10 Model: Exported from PyTorch using the LiteRT format and converted to TensorFlow Lite using TensorFlow's conversion tools.
2. Android Development: Built with Java/Kotlin, leveraging the CameraX API for real-time video streaming and object detection.
3. Performance Optimization:
   - Model quantized for faster inference.
   - Optimized for low-power mobile devices without compromising accuracy.

# 📊 Results
1. Detection Speed: 30+ FPS on modern Android devices.
2. Model Size: Lightweight, ensuring faster app initialization.
3. Accuracy: Competitive with larger models while maintaining efficiency.
