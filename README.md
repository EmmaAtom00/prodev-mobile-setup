# Expo Go Setup Documentation

## Objective

Mobile development requires more computational resources than web development. To simplify development and testing, this project uses the **Expo Framework for React Native**, which allows applications to run directly on physical devices using **Expo Go**.

This document records the setup process for Expo Go and any challenges encountered.

---

## Prerequisites

The following tools were installed and verified before setting up Expo Go:

* **Node.js**: LTS version installed
* **IDE**: Visual Studio Code
* **Operating System**: macOS / Linux / Windows
* **Mobile Device**: Android or iOS smartphone
* **Internet Connection**: Required for Expo services

---

## Why Expo Go?

Expo Go allows developers to:

* Test React Native applications directly on a physical device
* Avoid installing and maintaining heavy emulators
* Support both Android and iOS from a single development environment
* Reduce hardware and setup complexity

---

## Expo Go Installation Steps

### 1. Visit Expo Go Website

* Open: [https://expo.dev/go](https://expo.dev/go)
* Selected the **latest Expo SDK version**

### 2. Install Expo Go on Mobile Device

* **Android**: Installed from the Google Play Store
* **iOS**: Installed from the Apple App Store

### 3. Launch Expo Go

* Opened the Expo Go app on the mobile device

### 4. Account Setup

* Created a new Expo account / Logged into an existing account
* Successfully logged in on the Expo Go app

---

## Verification

* Expo Go opened successfully
* App prompted for login and displayed the home screen
* Device is ready to scan QR codes from Expo projects

---

## Challenges Faced

| Issue                 | Description                                      | Solution                            |
| --------------------- | ------------------------------------------------ | ----------------------------------- |
| Network connectivity  | Device and computer were not on the same network | Connected both to the same Wi-Fi    |
| Login issues (if any) | Delayed verification email                       | Retried login after a few minutes   |
| App installation      | App store delay or compatibility warning         | Updated OS and retried installation |

*(If no issues were encountered, note: “No major challenges faced during setup.”)*

---

## Conclusion

Expo Go was successfully installed and configured on a physical mobile device. The setup enables real-device testing for React Native applications without the need for emulators, ensuring a smoother and more efficient development workflow.

---

## Next Steps

* Initialize an Expo project using `npx create-expo-app`
* Run the project and scan the QR code using Expo Go
* Begin mobile application development 