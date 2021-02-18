[![Angular](https://img.shields.io/badge/Angular-v11-red.svg)](https://angular.io)
[![iOS](https://img.shields.io/badge/iOS-white.svg)](https://angular.io)
[![Android](https://img.shields.io/badge/Android-green.svg)](https://angular.io)
[![Standard](https://img.shields.io/badge/Standard-Style-green.svg)](https://github.com/standard/standard)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://opensource.org/licenses/MIT)

## Description

A cross platform (iOS/Android/web) sample project to demonstrate facial expression recognition with [face-api.js](https://github.com/justadudewhohacks/face-api.js/) and [Ionic Capacitor](https://capacitorjs.com)(Angular).

<img src="https://user-images.githubusercontent.com/10786558/108345292-0b0bbe80-7219-11eb-9250-02116cc672c2.jpg" height='300px'>

## Prerequisites

- Install [Node.js](https://nodejs.org/en/download/)


## Setup and Run

- Clone the project and proceed to its directory in CLI

- `npm install` //run once to install dependencies

### web

- `npm start` //run the sample

- Browse to `http://localhost:4200`

### mobile

- `npx cap add android` and/or `npx cap add ios` //set up platform projects

- Open the project in your IDE of chocie to run on devices/simulators ...


## Project Structure

```
src —
    |- app  //TS source
    |- assets  //assets incl. SSDMobileNet dependencies
    |- environment  //environment variables
e2e -   //e2e tests
```

## Written By
Bryan Huang
