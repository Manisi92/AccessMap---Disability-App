# AccessMap

**AccessMap** is a Flutter app designed to help people with disabilities navigate cities more easily and accessibly. The app uses Google Maps, voice recognition, and text-to-speech functionality to provide accessible navigation instructions and voice commands.

## Features
- **Interactive Map** with real-time user location tracking.
- **Voice Instructions** step-by-step using Text-to-Speech (TTS).
- **Voice Recognition** to trigger actions such as searching for accessible routes.
- Integration with **Google Maps Directions API** to fetch routes and display them on the map.
- Optimized for **accessibility** for users with visual impairments, compatible with TalkBack (Android) and VoiceOver (iOS).

## Technologies Used
- **Flutter**: Cross-platform framework for building native applications.
- **Google Maps SDK**: To integrate map features and directions.
- **flutter_tts**: To convert text into speech (TTS).
- **speech_to_text**: To convert speech to text for voice recognition.
- **Google Directions API**: To fetch directions and calculate accessible routes.

## Installation

### Prerequisites
Make sure you have Flutter and Android Studio (or your preferred IDE) set up on your machine.

1. **Install Flutter**: Follow the official Flutter installation guide: [flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install).
2. **Install Android Studio** (if you don't already have it): Download from [developer.android.com/studio](https://developer.android.com/studio).

### Setup the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AccessMap.git
   cd AccessMap
   Get the required dependencies:

flutter pub get

Set up your Google Maps API key:

    Create a project in the Google Cloud Console.
    Enable the following APIs: Google Maps SDK for Android/iOS and Google Directions API.
    Generate an API key and replace YOUR_API_KEY_HERE in android/app/src/main/AndroidManifest.xml (for Android) and ios/Runner/Info.plist (for iOS).

Run the app:

    For Android/iOS:

        flutter run

        Or use Android Studio to run the app on a physical device or emulator.

Usage

    Voice Command: Tap the microphone button to start listening for a command like "find accessible route" to get a walking path to a destination.
    Voice Navigation: The app will guide you with spoken instructions through the route as you move.
    Map: The app will display the user's location on the map, and trace the route to the destination.

Testing

    Testing on Android/iOS devices:
        You can test the app on a physical Android or iOS device, or use an Android emulator.
        Ensure that your USB Debugging (for Android) or Developer Mode (for iOS) is enabled.

    Accessibility:
        Test the app with TalkBack on Android or VoiceOver on iOS to ensure accessibility.

Contributing

Feel free to fork the repository and submit pull requests for bug fixes, features, or improvements. If you encounter any issues or have ideas for new features, open an issue in the GitHub repository.
License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    Thanks to Google for the Maps API and Directions API.
    Thanks to the Flutter community for providing such a powerful framework for cross-platform development.
