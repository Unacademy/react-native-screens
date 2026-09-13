# react-native-screens

> Native navigation primitives for your React Native app.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**react-native-screens** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

Native navigation primitives for your React Native app.

**Topics / Tags:** `approvers-1`

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | React Native |
| **Package Manager** | — |

### Dependencies

**Dev Dependencies:**
- `@babel/core`
- `@react-native-community/bob`
- `@react-navigation/native`
- `@react-navigation/stack`
- `@types/jest`
- `@types/react`
- `@types/react-native`
- `@types/react-test-renderer`
- `@typescript-eslint/eslint-plugin`
- `@typescript-eslint/parser`


---

## Repository Structure

```
react-native-screens/
├── .buckconfig
├── .eslintrc.js
├── .flowconfig
├── .gitattributes
├── .gitignore
├── .npmignore
├── .prettierrc.js
├── .watchmanconfig
├── Example/
│   ├── .babelrc
│   ├── .buckconfig
│   ├── .flowconfig
│   ├── .gitattributes
│   ├── .gitignore
├── LICENSE
├── README.md
├── RNScreens.podspec
├── android/
│   ├── build.gradle
│   ├── gradle
│   ├── gradle.properties
│   ├── gradlew
│   ├── gradlew.bat
├── babel.config.js
├── createNativeStackNavigator
├── ios/
│   ├── RNSScreen.h
│   ├── RNSScreen.m
│   ├── RNSScreenContainer.h
│   ├── RNSScreenContainer.m
│   ├── RNSScreenStack.h
├── jest.config.js
├── native-stack/
│   ├── README.md
│   ├── package.json
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `Example/.babelrc` | Source file |
| `Example/.buckconfig` | Source file |
| `Example/.flowconfig` | Source file |
| `Example/.gitattributes` | Source file |
| `Example/.gitignore` | Source file |
| `Example/.watchmanconfig` | Source file |
| `Example/App.js` | Source file |
| `Example/android/app/build.gradle` | Source file |
| `Example/android/app/proguard-rules.pro` | Source file |
| `Example/android/app/src/main/AndroidManifest.xml` | Source file |
| `Example/android/app/src/main/java/com/swmansion/rnscreens/example/LifecycleAwareView.java` | Source file |
| `Example/android/app/src/main/java/com/swmansion/rnscreens/example/MainActivity.java` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
git clone git@github.com:unacademy/react-native-screens.git
cd react-native-screens
# Follow language-specific setup
```

### Available Scripts

```bash
# check-types
npm run check-types   # tsc --noEmit

# start
npm run start   # node node_modules/react-native/local-cli/cli.js start

# test
npm run test   # npm run format && npm run lint && npm run test:unit

# test:unit
npm run test:unit   # jest

# format
npm run format   # prettier --write --list-different './src/**/*.{js,ts,tsx}'

# lint
npm run lint   # eslint --ext '.js,.ts,.tsx' --fix src && npm run check-types

# precommit
npm run precommit   # lint-staged

# release
npm run release   # npm login && release-it

# prepare
npm run prepare   # bob build

```


---

## Running the Application

```bash
npm run start   # node node_modules/react-native/local-cli/cli.js start
```

---

## Infrastructure & CI/CD

- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> # react-native-screens

This project aims to expose native navigation container components to React Native. It is not designed to be used as a standalone library but rather as a dependency of a [full-featured navigation library](https://github.com/react-navigation/react-navigation).

## Installation

### iOS

Installation on iOS should be completely handled with auto-linking, if you have insured pods are installed after adding this module, no other actions should be necessary

### Android

On Android the View state is not persisted consistently across Activity restarts, which can lead to crash

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
