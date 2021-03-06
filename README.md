<img src="/docs/rnskwx-logo.jpg" alt="React Native Starter Kit" width="400" />

[![GitHub tag](https://img.shields.io/github/tag/mcnamee/react-native-starter-kit.svg?style=flat-square)](https://github.com/saahmadnejad/react-native-starter-kit-without-expo/tags)
[![GitHub contributors](https://img.shields.io/github/contributors/mcnamee/react-native-starter-kit.svg?style=flat-square)](https://github.com/saahmadnejad/react-native-starter-kit-without-expo/contributors)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/mcnamee/react-native-starter-kit/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/mcnamee/react-native-starter-kit.svg?style=flat-square)](https://github.com/saahmadnejad/react-native-starter-kit-without-expo/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/mcnamee/react-native-starter-kit.svg?style=flat-square)](https://github.com/saahmadnejad/react-native-starter-kit-without-expo/issues-closed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/mcnamee/react-native-starter-kit.svg?style=flat-square)](https://github.com/saahmadnejad/react-native-starter-kit-without-expo/issues-pr)

---

# React (Web + Native) Starter Kit Without Expo

#### For when you're looking to build 'the next big thing' for both web and native mobile.

<a href="http://react-boilerplate.mcnam.ee/"><img src="/docs/web-demo.jpg" alt="Web Demo" height="50" /></a>

---

## 👋 Intro

This boilerplate launches with a [React web app](https://reactjs.org/) and [React Native app](https://facebook.github.io/react-native/) sharing a single code base. It shares the 'business logic' (_i.e. models, containers_) across the platforms, whilst allowing flexibility in View components to ensure your project looks and feels native in each platform.

The project is _super_ helpful to kick-start your next project, as it provides a lot of the common tools you may reach for, all ready to go. Specifically:

- A shared React and React Native structure
- __Flux architecture__
    - [Redux](https://redux.js.org/docs/introduction/)
    - Redux Wrapper: [Rematch](https://github.com/rematch/rematch)
- __Routing and navigation__
    - [React Native Router Flux](https://github.com/aksonov/react-native-router-flux) for native mobile
    - [React Router](https://github.com/ReactTraining/react-router) for web
- __Data Caching / Offline__
    - [Redux Persist](https://github.com/rt2zz/redux-persist)
- __UI Toolkit/s__
    - [Native Base](https://nativebase.io/) for native mobile
    - [Bootstrap](https://getbootstrap.com/) for web
- __User authentication__ example through
    - [Firebase](https://firebase.google.com/)
- __API/Data example__
    - Shows how to read/write data from/to an external API (in our case, [Firebase](https://firebase.google.com/))
- __Code Linting__ with
    - [Airbnb's JS Linting](https://github.com/airbnb/javascript) guidelines

---

## 📖 Docs

- [Setup your own Firebase](/docs/firebase.md)
- [Understanding the file structure](/docs/file-structure.md)
- [FAQs & Opinions](/docs/faqs.md)
- [Testing, Deploying & Publishing](/docs/publishing.md)
- [Contributing to this project](/docs/contributing.md)

---

## 🚀 Getting Started

#### 1. Clone and Install

_*It's recommended that you install [React Native Debugger](https://github.com/jhen0409/react-native-debugger/releases) and open before `yarn start`._

```bash
# Clone the repo
git clone https://github.com/saahmadnejad/react-native-starter-kit-without-expo.git

# Install dependencies
yarn install
```

#### 2.1. Run the _React Native_ App

```bash
# Start the React Native packager
yarn start
```

And then in another terminal:
```bash
# Start the React Native packager
yarn android
```


#### 2.2. Run the _Web_ App

```bash
# Starts are local live-reload server at:
# http://localhost:3001
yarn run web
```

Via webpack, starts a localhost server on port 3001 [http://localhost:3001](http://localhost:3001).

- Save code and it auto refreshes
- Install [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) into Chrome to see the state of Redux

---

_If there's any other ideas presented in this repo, that you think worth mentioning - feel free open a pull request :)_
