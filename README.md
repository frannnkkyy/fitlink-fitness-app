# FitLink

<p>
  <img src="https://img.shields.io/badge/Status-Prototype-E7B93E?style=flat-square" alt="Prototype">
  <img src="https://img.shields.io/badge/React_Native-Mobile-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React Native">
  <img src="https://img.shields.io/badge/Expo-Platform-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo">
  <img src="https://img.shields.io/badge/Firebase-Backend-E0A92F?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
</p>

Mobile fitness application developed with **React Native and Expo**, designed as a prototype for managing fitness-related information and exploring connected training experiences.

The project combines cross-platform mobile development with Firebase services and a modular application structure.


## Overview

FitLink is a mobile application created to explore the development of a digital fitness platform using modern cross-platform technologies.

The application was built with React Native and Expo, using Expo Router for file-based navigation and Firebase for cloud-related functionality.

The project focuses on creating a structured mobile experience while applying concepts such as reusable components, navigation, cloud integration and mobile interface development.

## Implemented features

### Mobile experience

- Cross-platform mobile interface
- Fitness-oriented application screens
- File-based navigation with Expo Router
- Reusable React Native components
- Mobile-focused layouts and interactions
- Organized application navigation

### Application functionality

- Firebase integration
- Cloud-based application configuration
- Modular component architecture
- Custom React hooks
- Shared application constants
- Static asset management
- Expo development environment

## Technology stack

| Area | Technologies |
|---|---|
| Mobile application | React Native |
| Development platform | Expo |
| Navigation | Expo Router |
| Cloud services | Firebase |
| Languages | JavaScript, TypeScript |
| Development | Node.js, npm, Git |

## Project structure

    fitlink/
    ├── app/                    # Application screens and routes
    ├── assets/                 # Images and static resources
    ├── components/             # Reusable React Native components
    ├── constants/              # Shared application constants
    ├── hooks/                  # Custom React hooks
    ├── scripts/                # Development utilities
    ├── firebaseConfig.js       # Firebase configuration
    ├── app.json                # Expo application configuration
    ├── eslint.config.js        # ESLint configuration
    ├── package.json            # Dependencies and scripts
    ├── package-lock.json
    ├── tsconfig.json           # TypeScript configuration
    └── README.md

## Getting started

### Requirements

Install the following software before running the project:

- Node.js
- npm
- Git
- Expo Go or a compatible emulator

### Installation

Clone the repository:

    git clone https://github.com/frannnkkyy/fitlink.git

Open the project:

    cd fitlink

Install the dependencies:

    npm install

Start the Expo development server:

    npx expo start

The Expo development environment provides options to run the application using:

- Expo Go
- Android Emulator
- iOS Simulator
- Development Build
- Web browser

## Firebase configuration

The project includes Firebase integration through `firebaseConfig.js`.

For a public repository, Firebase configuration and other environment-specific values should be handled through environment variables when appropriate.

Sensitive credentials or administrative secrets should never be committed to the repository.

## Architecture

FitLink follows the file-based routing architecture provided by Expo Router.

Application screens are organized inside the `app` directory, while reusable interface elements are separated into `components`.

Custom application logic can be organized through `hooks`, while shared configuration and application values are maintained separately through `constants`.

This structure helps separate navigation, interface components and application logic as the project grows.

## Current limitations

This repository represents a prototype and is not intended as a production-ready fitness platform.

- The application is currently presented as a development prototype
- Production deployment has not been documented
- Automated tests are not currently documented
- Some functionality may require Firebase configuration
- Additional fitness and connected-device functionality can be expanded in future versions

## Roadmap

- [ ] Expand workout and fitness management features
- [ ] Improve user profile functionality
- [ ] Add training progress visualization
- [ ] Expand Firebase data integration
- [ ] Add automated testing
- [ ] Improve application error handling
- [ ] Document Firebase configuration with `.env.example`
- [ ] Add additional fitness statistics
- [ ] Expand connected fitness / IoT functionality
- [ ] Prepare a production mobile build

## What I learned

This project helped me practice:

- Developing cross-platform applications with React Native
- Working with the Expo development ecosystem
- Implementing file-based navigation with Expo Router
- Structuring mobile applications with reusable components
- Integrating Firebase into a mobile project
- Organizing application logic with React hooks
- Managing mobile application assets and configuration
- Using Git and GitHub for version control

## Author

**Carlos Constantino**

- Portfolio: [portafoliofrann.netlify.app](https://portafoliofrann.netlify.app/)
- LinkedIn: [linkedin.com/in/fcoocarlos](https://www.linkedin.com/in/fcoocarlos/)
- GitHub: [github.com/frannnkkyy](https://github.com/frannnkkyy)

## Project status

FitLink is a prototype developed for learning, experimentation and portfolio demonstration.

The repository showcases the mobile development architecture, React Native implementation, Expo ecosystem and Firebase integration explored during the project.
