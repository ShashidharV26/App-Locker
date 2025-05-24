# 🔒 App Locker

## 📱 Overview

**App Locker** is a lightweight, secure application designed for **Android TV OS** that restricts unauthorized users from accessing selected apps on the device. With a simple setup and user-friendly interface, the app uses a **custom password mechanism** and **accessibility services** to enforce restrictions and enhance parental or administrative control over app usage.

---

## ✨ Features

- 🔐 **Password Protection**  
  On the first launch, users must grant necessary permissions and set an **alphanumeric password** to control access.

- 🔁 **Toggle Lock Feature**  
  Easily enable or disable the app lock functionality via a built-in toggle switch.

- 📲 **App Selection**  
  Users can choose which applications to lock by navigating to a system-level app list and selecting specific apps.

- 🔄 **Persistent Lock**  
  Once app lock is enabled, any attempt to open the selected apps prompts for the password.

- 📋 **Secure & Private**  
  All user configurations are stored **locally** using **Room Database**, ensuring user data is secure and never exposed.

---

## 🛠 Tech Stack

| Feature Area              | Technology Used             |
|---------------------------|-----------------------------|
| Programming Language      | Kotlin                      |
| UI Framework              | Jetpack Compose             |
| Architecture              | MVVM                        |
| Background Monitoring     | Accessibility Service       |
| Local Data Storage        | Room Database               |
| State Management          | ViewModel & LiveData        |

---

## 💡 Future Improvements

- Support for biometric authentication.
- Option to recover or reset password.
- Admin mode with more customization.

  
