# CheckHotDog-Swift

# Features

**Real-time Image Recognition:** The app uses the device's camera or photo library to capture or select images, and then processes them in real-time to determine if the image contains a hotdog or not.

**CoreML and Vision Integration:** The app leverages CoreML, Apple's machine learning framework, combined with the Vision framework to perform the image recognition task. It utilizes a pre-trained model specifically designed for hotdog classification.

**Simple and Intuitive UI:** The user interface is designed to be straightforward and user-friendly. Users can easily capture photos or choose images from the photo library, and the app will provide instant feedback on whether the image contains a hotdog or not.

# Requirements

iOS 14.0+

Xcode 12.0+

Swift 5.0+

# Installation

1. Clone or download this repository.
2. Open the project in Xcode.
3. Build and run the app on a simulator or a physical device running iOS 14.0 or later.

# Usage

1. Launch the app on your device.
2. Grant the necessary permissions for accessing the device's camera and photo library.
3. The app will open the camera view by default. Point the camera at an object or scene and the app will analyze the image in real-time.
4. Alternatively, tap the photo library button to select an image from your device's photo library. The app will analyze the selected image.
5. The app will display the result of the image recognition, indicating whether the image contains a hotdog or not.

# Resources

The app's machine learning model for hotdog classification is trained using a dataset from InceptionV3. The model is trained using the CoreML framework and included in the app's bundle.

# Screenshots

<div>
  <img src="https://github.com/fenil0613/CheckHotDog-Swift/assets/93746209/577e6186-aec7-47f4-b6ce-caefb989d300" alt="Hotdog Image" width="210">
  <img src="https://github.com/fenil0613/CheckHotDog-Swift/assets/93746209/78ef4727-afd2-4b40-853c-d2f6de3bd63b" alt="Not Hotdog Image" width="210">
</div>

