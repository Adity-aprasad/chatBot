# ChatBot

A React Native mobile app with an intelligent chatbot powered by OpenAI's API and Firebase integration.

## Overview

This repository contains a mobile application built with React Native that features a sophisticated chatbot system. The app leverages Firebase for user authentication and real-time data storage, while utilizing OpenAI's API to provide intelligent conversational capabilities.

## Features

- **User Authentication**: Complete login and registration system using Firebase Authentication
- **Real-time Database**: Firebase Realtime Database integration for persistent chat history and user data
- **AI-Powered Conversations**: Integration with OpenAI API for natural language processing and intelligent responses
- **Cross-Platform**: Works on both iOS and Android devices
- **Real-time Updates**: Instant message delivery and synchronization across devices
- **User-Friendly Interface**: Intuitive chat interface with modern design

## Prerequisites

- Node.js (v14 or newer)
- npm or yarn
- React Native CLI
- Firebase account
- OpenAI API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Adity-aprasad/chatBot.git
cd chatBot
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env` file in the root directory with your API keys:
```
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_DATABASE_URL=your_firebase_database_url
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id

OPENAI_API_KEY=your_openai_api_key
```

4. Run the application:
```bash
# For iOS
npx react-native run-ios

# For Android
npx react-native run-android
```

## Project Structure

```
chatBot/
├── android/                # Android native files
├── ios/                    # iOS native files
├── src/
│   ├── components/         # Reusable UI components
│   ├── screens/            # Screen components
│   ├── services/           # API services
│   ├── utils/              # Utility functions
│   ├── navigation/         # Navigation configuration
│   ├── redux/              # State management (if used)
│   └── firebase/           # Firebase configuration
├── App.js                  # Main application component
└── ...
```

## Firebase Setup

1. Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Authentication with Email/Password sign-in method
3. Set up Realtime Database with appropriate security rules
4. Add your application to the Firebase project and download configuration
5. Update the `.env` file with your Firebase configuration

## OpenAI API Integration

1. Sign up for an OpenAI API key at [OpenAI](https://openai.com/api/)
2. Add your API key to the `.env` file
3. The chatbot service is configured to use OpenAI's models for generating responses

## Usage

After installing and running the app:

1. Register a new account or log in with existing credentials
2. Start a new conversation with the AI chatbot
3. Chat histories will be automatically saved to Firebase in real-time
4. Access your conversations from any device with your account

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Aditya Prasad - [@Adity_aprasad](https://github.com/Adity-aprasad)

Project Link: [https://github.com/Adity-aprasad/chatBot](https://github.com/Adity-aprasad/chatBot)
