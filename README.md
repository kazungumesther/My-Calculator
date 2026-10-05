# Calculator App

A cross-platform mobile application built using Flutter to perform basic and advanced mathematical calculations within a clean layout.

---

##  Live Demo

Check out the source repository and track updates here:  
**(https://github.com/kazungumesther/My-Calculator/tree/main)**

---

##  Features

*   **Basic Arithmetic:** Perform addition, subtraction, multiplication, and division operations.
*   **Clear & Delete Functions:** Easily reset the entire display panel or remove individual numerical input errors.
*   **Decimal Point Precision:** Supports continuous floating-point operations for precise mathematical evaluations.
*   **Grid Keypad Interface:** Responsive button mapping designed for smooth tap gestures on mobile viewports.

---

##  Tech Stack

*   **Framework:** [Flutter / Dart](https://flutter.dev) (Multiplatform native target builds)
*   **Architecture Pattern:** Clean layout separation isolating calculations from structural widget components.

---

##  Suggested Project Structure

```text
calculator_app/
├── lib/
│   ├── components/
│   │   ├── display_panel.dart    # Manages the calculation result and input text view strings
│   │   └── calculator_button.dart # Handles tap animation states and individual event triggers
│   ├── screens/
│   │   └── home_screen.dart      # Main user interface viewport layout grid mounting
│   └── main.dart                 # Application engine initialization entry
└── test/
    └── widget_test.dart          # User interface interaction tests
```

---

##  Getting Started

Follow these steps to set up and launch the Calculator App on your machine locally.

###  Prerequisites

Ensure your system platform environment has the **Flutter SDK** and **Dart SDK** installed and configured within your global environment variables.

###  Local Setup

1. Clone this repository workspace:
   ```bash
   git clone https://://github.com.git
   ```

2. Direct your terminal shell into the root project directory:
   ```bash
   cd calculator_app
   ```

3. Download the required dependencies:
   ```bash
   flutter pub get
   ```

###  Running the Application

To boot up the application on a connected device or local virtual emulator:

```bash
flutter run
```

---

##  Testing Suite Validation

To execute the verification layout tests:

```bash
flutter test
```
