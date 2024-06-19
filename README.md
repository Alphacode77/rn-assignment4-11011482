# rn-assignment4-11011482

# React Native Tab Navigation App

This is a simple React Native application that demonstrates the use of bottom tab navigation with three components: `Frame`, `LogIn`, and `Homepage`.

# Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
  - [Frame](#frame)
  - [LogIn](#login)
  - [Homepage](#homepage)
- [Screenshots](#screenshots)

# Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

# Install the dependencies

bash
npm install
Run the app:
bash

npx react-native run-android   # For Android
npx react-native run-ios       # For iOS

## Usage

The app uses a bottom tab navigator to switch between three screens: Frame, LogIn, and Homepage.

# Components

## Frame

The Frame component is the first tab in the navigation. It serves as the initial screen when the app is launched. This component can be used to display introductory information or any initial content you want the user to see.

## javascript

import React from 'react';
import { View, Text } from 'react-native';

const Frame = () => (
  <View>
    <Text>Frame</Text>
  </View>
);

export default Frame;

## LogIn

The LogIn component is the second tab in the navigation. It provides a login interface for users to authenticate themselves. This component typically includes form fields for the username and password and a button to submit the login form.

## javascript

import React from 'react';
import { View, Text } from 'react-native';

const LogIn = () => (
  <View>
    <Text>LogIn</Text>
  </View>
);

export default LogIn;

## Homepage

The Homepage component is the third tab in the navigation. It serves as the main content area of the app, where users can access the primary features and information.

## javascript

import React from 'react';
import { View, Text } from 'react-native';

const Homepage = () => (
  <View>
    <Text>Homepage</Text>
  </View>
);

export default Homepage;

# Screenshots

![Frame 1](./JobSearch/assets/Frame%201.jpg)
![Login page](./JobSearch/assets/Login%20page.jpg)
![home page](./JobSearch/assets/home%20page.jpg)
