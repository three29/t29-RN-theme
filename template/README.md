# Welcome to T29 RN Theme

## The latest and greatest theme from [Three29](htts://three29.com), out of Sacramento CA. this theme was designed to speed up our app setup time. It comes preconfigured to use the following packages. It also has esLint configured and Prettier configured.

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

**Components**
This is where your React components will live. Each component will have a directory containing the `.js` file, along with a style file inside `Styles` folder. The app will come with some commonly used components like Button.

**Config**
This is where all of your app configuration located like Reactotron config, error loging config, etc.

**Containers**
This is the entire point of the app. Inside this directory you will find `app.js` and `rootContainer.js`. app.s is the main entire point and loads your redux store. rootContainer.js configures your style bar and loads your navigation. you will also find a `Screens` directory. This is where your screen components will live. A screen is a React component which will take up the entire screen and be part of the navigation hierarchy. Each screen will have a directory containing the `.js` file, along with style file inside `Styles` folder.

**Images** This is where all of your local image assets will live. Store all local image asset file and register each image inside `index.js` file.

**Lib** This is where your custom library will live. You can put utility tools, string converter, or any custom helper here.

**Navigation** This is where your navigation will live. All of your live screens will be registered.

**Redux** This is where your Redux will live.

**Services** This is where your app services will live.

**Themes** This is where your app themes will live.

### ./Tests directory (COMING SOON)

This directory will hold your Jest configs and mocks, as well as your storyshots test file. This is a file that contains the `snapshots` of all your component.

## Running your App

### Prerequisites:

- Make sure you already setup React Native environtment (Android SDK, Java, etc.)

### How to Setup

**Step 1:** git clone this repo

**Step 2:** cd to the cloned repo

**Step 3:** Install the Application with `yarn install` or `npm install`

**Step 4:** Run `npx pod-install` for iOS only

### Run the CLI:

1. cd to the cloned repo
2. Run Build for either OS

- for iOS
  - run `npm run ios`
- for Android
  - run `npm run android`
