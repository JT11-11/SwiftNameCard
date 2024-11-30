# SwiftNameCard

This Swift Playground project demonstrates the use of **SceneKit** to display a 3D model of a fish (as an example) and features a dynamic quote generator. The app displays a 3D model that can be manipulated with camera controls, and a button generates a random quote when tapped.

### Disclaimer

The fish model used in this project (`fish.usdz`) is **just an example** and is not a model that I personally own. The fish model is provided as a placeholder to demonstrate how to render and interact with 3D objects using SceneKit in a SwiftUI-based app. The model is used for educational purposes in this project.

---

## Features

- **3D Fish Model**: Display a 3D fish model that can be rotated and zoomed using camera controls.
- **Quote Generator**: Randomly generates a motivational quote when the user taps a button.
- **Customizable UI**: A clean, gradient background and modern design for displaying quotes and contact information.

---

## Tech Stack

- **SwiftUI**: For building the user interface.
- **SceneKit**: For displaying and interacting with 3D models.
- **UIKit**: Used for managing the background of the 3D scene.

---

## Requirements

- **Xcode 12 or later**
- **iOS 14.0 or later** (or macOS equivalent)
- A **Swift Playground** environment or a **SwiftUI-based app** project

---

## Getting Started

To run the project, follow these steps:

1. Open the project in **Xcode**.
2. Ensure the `fish.usdz` file is available in your project. You can find a fish model online (e.g., on Apple’s ARKit resources) or use any `.usdz` model to replace the fish model.
3. Open the `ContentView.swift` file to see the code and the UI in action.
4. Press the **Run** button to start the Playground or App in the **iOS Simulator** or on a **real device**.

---

## Code Overview

The main view (`ContentView`) consists of:

- A **3D fish model** displayed using `SceneKit` inside a `SceneView`. The model can be interacted with (rotated, zoomed, etc.) thanks to the `allowsCameraControl` option.
- A **gradient background** created with `LinearGradient` for a visually appealing design.
- A **quote generator** that displays a new quote each time the user taps the "Generate Quote" button. The quotes are stored in an array and randomly selected when the button is tapped.
- A section displaying **contact information** and a **location** using icons and text.

---
