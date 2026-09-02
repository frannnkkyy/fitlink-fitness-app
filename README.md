# FitLink — IoT Wearable & Mobile Health Application

<p>
  <img src="https://img.shields.io/badge/Status-Prototype-E7B93E?style=flat-square" alt="Prototype">
  <img src="https://img.shields.io/badge/React_Native-Mobile-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React Native">
  <img src="https://img.shields.io/badge/Expo-Platform-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo">
  <img src="https://img.shields.io/badge/Arduino-Wearable-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/Firebase-Realtime_Database-E0A92F?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
  <img src="https://img.shields.io/badge/IoT-Connected_Device-4C8BF5?style=flat-square" alt="IoT">
</p>

Mobile IoT application connected to an **Arduino-based wearable device** for monitoring health and activity information, including steps, BPM, blood pressure and blood oxygen measurements.

FitLink combines mobile development, sensors and Firebase Realtime Database to synchronize wearable measurements with a mobile application, visualize health data and review previous measurement sessions.


## Overview

FitLink is a mobile application and wearable-device prototype designed to explore the integration of mobile software with IoT hardware and health-related sensors.

The project connects an Arduino-based wearable with a mobile application that displays activity and measurement information. Firebase Realtime Database is used to manage synchronized data between the application and the connected system.

The application provides access to step count, BPM, blood pressure and blood oxygen information, as well as charts for pulse and oxygen measurements and a session history for reviewing previous records.

## Implemented features

### Mobile application

- Mobile interface for health and activity information
- Step count visualization
- BPM monitoring
- Blood pressure measurements
- Blood oxygen measurements
- Pulse data visualization
- Blood oxygen charts
- Historical measurement sessions
- Navigation between application sections

### IoT and data integration

- Arduino-based wearable integration
- Health and activity sensor integration
- Firebase Realtime Database
- Synchronization of wearable measurements with the mobile application
- Storage of measurement sessions
- Retrieval of previous measurements
- Frontend and backend functionality for the connected application

## Technology stack

| Area | Technologies |
|---|---|
| Mobile application | React Native, Expo |
| IoT hardware | Arduino-based wearable |
| Data and backend | Firebase Realtime Database |
| Hardware integration | Sensors |
| Navigation | Expo Router |
| Languages | JavaScript, TypeScript |
| Development | Node.js, npm, Git |

## System architecture

FitLink connects a wearable device with a mobile application through a cloud-based data layer.

    Wearable sensors
          │
          ▼
    Arduino-based device
          │
          ▼
    Firebase Realtime Database
          │
          ▼
    FitLink mobile application
          │
          ├── Activity information
          ├── Health measurements
          ├── Pulse and oxygen charts
          └── Session history

The wearable collects health and activity information, while Firebase Realtime Database provides the data layer used by the mobile application to access and display measurements.

## Project structure

    fitlink/
    ├── app/                    # Application screens and routes
    ├── assets/                 # Images and static resources
    ├── components/             # Reusable mobile components
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

Install the following software before running the mobile project:

- Node.js
- npm
- Git
- Expo Go or a compatible emulator

A Firebase project is also required for the application's data functionality.

### Installation

Clone the repository:

    git clone https://github.com/frannnkkyy/fitlink.git

Open the project:

    cd fitlink

Install the dependencies:

    npm install

Start the Expo development server:

    npx expo start

The application can then be opened using Expo Go or a compatible development environment.

## Firebase configuration

FitLink uses Firebase Realtime Database for application data and synchronization.

The repository includes Firebase configuration through `firebaseConfig.js`. Environment-specific configuration should be kept outside the public source code when preparing the project for production.

Sensitive credentials or administrative secrets should never be committed to the repository.

## Wearable integration

The mobile application was developed alongside an Arduino-based wearable device.

The connected system integrates sensor measurements used by FitLink to display:

- Step count
- BPM
- Blood pressure
- Blood oxygen

The application also provides pulse and oxygen charts and stores measurement sessions so previous information can be reviewed.

## Current limitations

This repository represents a prototype and is not intended to be used as a certified medical system.

- The project was developed as an IoT and mobile application prototype
- Health measurements are presented as information from the connected prototype
- The system is not intended for medical diagnosis
- Production deployment has not been configured
- Automated tests are not currently documented
- Hardware operation requires the corresponding wearable prototype and sensors

## Roadmap

- [ ] Improve wearable-to-application communication
- [ ] Expand health and activity visualization
- [ ] Improve historical measurement analysis
- [ ] Add additional charts and statistics
- [ ] Improve application error handling
- [ ] Add automated tests
- [ ] Move Firebase configuration to environment variables
- [ ] Document the wearable hardware setup
- [ ] Document sensor connections and configuration
- [ ] Prepare a production mobile build

## What I learned

This project helped me practice:

- Developing a mobile application connected to IoT hardware
- Integrating an Arduino-based wearable with software services
- Working with health and activity sensors
- Developing frontend and backend functionality for a connected application
- Using Firebase Realtime Database
- Synchronizing data between hardware and a mobile interface
- Visualizing pulse and blood oxygen information
- Managing historical measurement sessions
- Structuring a mobile application with reusable components
- Using Git and GitHub for version control

## Project context

FitLink was developed in 2025 as a mobile and IoT software project.

The repository demonstrates the integration of mobile development, Firebase Realtime Database, Arduino-based hardware and sensors through a wearable companion application.

## Author

**Carlos Constantino**

- Portfolio: [portafoliofrann.netlify.app](https://portafoliofrann.netlify.app/)
- LinkedIn: [linkedin.com/in/fcoocarlos](https://www.linkedin.com/in/fcoocarlos/)
- GitHub: [github.com/frannnkkyy](https://github.com/frannnkkyy)

## Project status

FitLink is a functional prototype developed for learning and portfolio demonstration.

The project showcases mobile development, IoT integration, Firebase data management and the connection between a wearable device and a mobile application.
