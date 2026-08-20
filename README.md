# Android Hello World Application

## Experiment 1: Hello World Android Application

### Aim
To develop a simple Android application that displays the message **"Hello World!"** using a TextView.

---

## Objective
- Learn the basic structure of an Android application.
- Design a simple user interface using XML.
- Display text using a TextView.
- Run the application on an Android Emulator.

---

## Technologies Used
- Android Studio
- Kotlin
- XML
- Android SDK
- Gradle

---

## Concept

Android applications are built using **Activities** and **XML layouts**.

- **MainActivity.kt** is the entry point of the application.
- **activity_main.xml** defines the user interface.
- **TextView** is used to display text on the screen.
- The application is executed using an Android Emulator.

---

## Scenario

A simple Android application is developed to display **"Hello World!"** in the center of the screen. The application demonstrates the basic Android project structure and the use of a TextView.

---

# Project Folder Structure

```text
Android-HelloWorld/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   └── values/
│   │   │   │       └── strings.xml
│   │   │   └── AndroidManifest.xml
│
├── Screenshot/
│   ├── output.png
│   ├── testcase1.png
│   └── testcase3_name.png
│
├── README.md
├── build.gradle.kts
└── settings.gradle.kts
```

---

# Output

The application displays the following message:

**Hello World!**

### Output Screenshot

![Output](Screenshot/output.png)

---

# Test Cases

## Test Case 1

**Test Case ID:** TC-01

**Objective:** Verify that the application launches successfully.

**Input:** Launch the application.

**Expected Result:** The application opens successfully and displays **Hello World!**

**Actual Result:** Pass

**Screenshot:**

![Test Case 1](Screenshot/testcase1.png)

---

## Test Case 2

**Test Case ID:** TC-02

**Objective:** Verify that the application continues to display the message after reopening.

**Input:** Close and reopen the application.

**Expected Result:** The application displays **Hello World!**

**Actual Result:** Pass

**Screenshot:**

![Test Case 2](Screenshot/output.png)

---

# Conclusion

The experiment was successfully completed. A simple Android application was developed using Android Studio. The application demonstrates the use of an Activity and a TextView to display text on the screen.

---

## Author

**Name:** Lathika

**Course:** MCA

**Subject:** Android Application Development
