# UOL Transport Desk

UOL Transport Desk is a basic Android application developed using **Java, XML, and Android Studio** as part of the Mobile Application Development lab task at the University of Lahore.

The application provides access to university-related services and demonstrates Android Intents, activity navigation, data passing, and input validation.

## Features

- **University Website:** Opens the University of Lahore website in a browser.
- **Office Contact:** Opens the phone dialer with the university office number.
- **Bus Stop Location:** Opens the requested location in Maps.
- **Problem Reporting:** Opens a second screen to enter contact details.
- **Phone Validation:** Checks the Pakistani mobile number format.
- **Email Validation:** Checks the format of the entered email address.
- **Data Passing:** Passes the student's name from the main screen to the problem-reporting screen.

## Technologies Used

- Java
- XML
- Android Studio
- Android Intents

## Android Concepts Demonstrated

### Implicit Intents
Used to open external applications such as the browser, phone dialer, Maps, and email application.

### Explicit Intents
Used to navigate from `MainActivity` to `ProblemActivity`.

### Intent Extras
Used to pass the student's name between activities.

### Input Validation
Used to check the student's name, phone number, and email address and display errors for invalid input.

## Project Structure

```text
UOLTransportDesk/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/example/uoltransportdesk/
│           │       ├── MainActivity.java
│           │       └── ProblemActivity.java
│           ├── res/
│           │   ├── layout/
│           │   │   ├── activity_main.xml
│           │   │   └── activity_problem.xml
│           │   └── drawable/
│           └── AndroidManifest.xml
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open the project in Android Studio.
3. Allow Gradle to sync and install any required dependencies.
4. Run the application on an Android emulator or a connected Android device.
5. Test the website, dialer, Maps, problem-reporting, and validation features.

## Student Information

- **Student Name:** Arisha Fatima
- **SAP ID:** Add your SAP ID
- **Section:** Add your section
- **Course:** Mobile Application Development
- **University:** The University of Lahore

## Purpose

This project was developed for academic learning and demonstrates basic Android application development using Java and XML.
