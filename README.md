# StickerSmash - Create Custom Stickers 🎨

## 📱 Overview

StickerSmash is a cross-platform application built with Expo that lets you create custom stickers by adding fun emoji and stickers to your photos. Upload an image, customize it with our collection of stickers, and save your creation to share with friends!

<img width="333" alt="Screenshot 2024-11-18 at 3 53 32 PM" src="https://github.com/user-attachments/assets/bdff195d-6589-4dfa-802b-47cc41ab0575">

## ✨ Features

- 🖼️ Upload photos from your device
- 🎯 Place and position stickers with precise control
- 👆 Drag-and-drop interface for easy customization
- 💾 Save your creations to your device
- 📱 Works on iOS, Android, and Web
- 🎨 Collection of emoji stickers to choose from
- ↩️ Undo/Redo functionality
- 📏 Resize and rotate stickers

## 🛠️ Technologies Used

- [Expo](https://expo.dev/)
- [React Native](https://reactnative.dev/)
- [Expo Router](https://docs.expo.dev/router/introduction/)
- [Expo Image Picker](https://docs.expo.dev/versions/latest/sdk/imagepicker/)
- [React Native Gesture Handler](https://docs.swmansion.com/react-native-gesture-handler/)
- [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/)
- [dom-to-image](https://github.com/tsayen/dom-to-image) (Web)
- [react-native-view-shot](https://github.com/gre/react-native-view-shot) (Mobile)

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js
- npm/yarn
- Expo CLI
- [Optional] Android Studio for Android development
- [Optional] Xcode for iOS development

## ⚙️ Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npx expo start
```

In the output, you'll find options to open the app in a:
- [Development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go)

## 🎯 How to Use

1. **Select an Image**
   - Tap the "Pick a photo" button to choose an image from your device
   - The image will be loaded into the editor

2. **Add Stickers**
   - Press the "Add Sticker" button to open the sticker picker
   - Select from our collection of emoji stickers
   - Tap anywhere on the image to place the sticker

3. **Customize Stickers**
   - Drag stickers to reposition them
   - Use pinch gestures to resize
   - Double tap to remove a sticker

4. **Save Your Creation**
   - Press the "Save" button to save your creation
   - On mobile, the image will be saved to your photo gallery
   - On web, the image will be downloaded to your device

## 🚀 Get a Fresh Project

When you're ready to start from scratch, run:
```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## 📱 Development

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## 📚 Learn More

To learn more about developing your project with Expo:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## 🤝 Join the Community

Join our community of developers creating universal apps:

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

<div align="center">
  <small>Built with ❤️ using Expo</small>
</div>
