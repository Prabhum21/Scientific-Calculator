# 🧮 Scientific Calculator Android App

A comprehensive scientific calculator application for Android, built with Kotlin. This app provides a wide range of mathematical operations from basic arithmetic to complex scientific functions.

## ✨ Features

- **Basic Operations**: Addition, subtraction, multiplication, and division.
- **Scientific Functions**:
  - **Trigonometry**: `sin`, `cos`, `tan`.
  - **Logarithms**: `log` (base 10), `ln` (natural log).
  - **Power & Roots**: Square, square root, exponentiation (`^`).
  - **Factorials**: Sequential integer calculations.
- **Constants**: Direct support for Pi (π).
- **Expression Evaluation**: Support for complex expressions with parentheses and operator precedence.
- **Dual Display**: Shows current input and previous results/expressions.

---

## 🛠 Technology Stack

### Core Technologies
- **Platform**: Android
- **Programming Language**: [Kotlin](https://kotlinlang.org/) v1.7.20
- **Build System**: [Gradle](https://gradle.org/) (Android Gradle Plugin v7.3.1)
- **Min SDK**: 28 (Android 9.0 Pie)
- **Target SDK**: 32 (Android 12L)
- **UI System**: XML Layouts (Android View System)

### Key Libraries & Frameworks
- **AndroidX AppCompat**: For backward compatibility.
- **AndroidX ConstraintLayout**: For efficient and flexible UI designs.
- **AndroidX CardView**: For specialized UI components with rounded corners and shadows.
- **Material Design**: Standard Android UI components.

---

## 🧠 Architecture & Logic

- **Design Pattern**: Single Activity Architecture (`MainActivity`).
- **Mathematical Evaluation**: Custom expression parser implemented using a **recursive descent parsing** approach to handle operator precedence and mathematical functions.
  - **Supports**: Arithmetic, Trigonometry (sin, cos, tan), Logarithms (log, ln), Square Root, Powers, and Factorials.

---

## 🚀 Getting Started

1. **Clone** this repository.
2. Open the project in **Android Studio** (Flamingo or later recommended).
3. **Build** the project using Gradle.
4. **Run** the app on an Android Emulator or a physical device (API 28+).

### Development Environment
- **Kotlin Version**: Optimized for JVM 1.8.
- **Target OS**: Android 9.0+

---

## 📂 Project Structure

- `app/src/main/java`: Contains the Kotlin source code (`MainActivity.kt`).
- `app/src/main/res/layout`: Contains the UI layout files (`activity_main.xml`).
- `app/build.gradle`: Project dependencies and SDK configurations.

---

## 📜 License

This project is for educational purposes.
