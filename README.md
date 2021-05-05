
## Intro

The gym app consists of [React web app](https://reactjs.org/) and [React Native app](https://facebook.github.io/react-native/). It shares the 'business logic' (_i.e. models, containers_) across the platforms, whilst allowing flexibility in View components to ensure the project looks and feels native in each platform.

A lot of common tools you may reach for. Specifically:

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
- __Simpler mobile app development__ through
    - [Expo](https://expo.io/)
- __User authentication__ example through
    - [Firebase](https://firebase.google.com/)
- __API/Data example__
    - Shows how to read/write data from/to an external API (in our case, [Firebase](https://firebase.google.com/))
- __Code Linting__ with
    - [Airbnb's JS Linting](https://github.com/airbnb/javascript) guidelines

---

## Getting Started

#### 0. Prerequisites
Make sure you have Expo CLI installed
```bash
npm install -g expo-cli
```

#### 1. Clone and Install

```bash
# Clone the repo
'git clone' the develop branch into your system

# Install all dependencies
yarn install
```

#### 2.1. Run the _Web_ App

```bash
# Starts are local live-reload server at:
# http://localhost:3000
yarn run web
```

Via webpack, starts a localhost server on port 3001 [http://localhost:3001](http://localhost:3001).

- Save code and it auto refreshes
- Install [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) into Chrome to see the state of Redux


#### 2.2. project management tool and codes commit

Project Management Tool: github project management tool to assign work
Git: using git flow - https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
# dun-hollow
