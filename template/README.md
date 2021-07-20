# Welcome to T29 RN Theme template

## Tech Stack

- React Native (0.64)
- React Navigation 5
- Redux
- redux ToolKit
- Reactron
- OsmiCSX (Tailwind theme)

## Quick Start

Project's Structure will look similar to this:

```
Project-Name
├── App
│   ├── Components
│   ├── Config
│   ├── Containers
│   ├── Images
│   ├── Libs
│   ├── Navigation
│   ├── Redux
│   ├── Services
│   ├── Themes
├── Tests (COMING SOON)
│   ├── Components
│   ├── Services
│   ├── Setup.js
├── android
│   ├── app
│   ├── build.gradle
│   ├── gradle
│   ├── gradle.properties
│   ├── gradlew
│   ├── gradlew.bat
│   ├── keystores
│   └── settings.gradle
├── ios
│   ├── OsmiApp
│   ├── OsmiApp-tvOS
│   ├── OsmiApp-tvOSTests
│   ├── OsmiApp.xcodeproj
│   └── OsmiAppTests
├── .buckconfig
├── .eslintignore
├── .eslintrc.json
├── .flowconfig
├── .gitattributes
├── .gitignore
├── .prettierrc.json
├── .watchmanconfig
├── app.json
├── babel.config.js
├── index.js
├── metro.config.js
├── package.json
└── README.md
```

### ./App directory

This is a directory you would normally have to create when using vanilla React Native.

The inside of the src directory looks similar to the following:

```
App
├── Components
├── Config
├── Containers
├── Images
│── Libs
├── Navigation
├── Redux
├── Services
└── Themes
```

## Running your App

1. cd to the project
2. Run Build for either OS

- for iOS
  - run `npm run ios`
- for Android
  - run `npm run android`
