# Flutter Counter App

## Project Overview

The **Flutter Counter App** is a simple app with a single view. It demonstrates basic state management and interaction handling in Flutter by allowing the user to increment, decrement, and reset a counter. 

The app consists of a central display showing the current count and three buttons: 
- An increment button that increases the count by 1. 
- A decrement button that decreases the count by 1, but the counter will not go below 0. 
- A reset button that resets the counter back to 0.

### Screenshots

![Flutter Counter App](https://github.com/user-attachments/assets/6033dc27-a206-49dc-b339-9f4603daeca0)


## Features

1. **AppBar**: A top bar with the title "Flutter Counter App."
2. **Counter Display**: A large text widget that displays the current count in the center of the screen, starting at 0.
3. **Increment Button**: A floating action button (FAB) at the bottom-right of the screen that increments the counter by 1 when tapped.
4. **Decrement Button**: A second floating action button (FAB) placed at the bottom-left of the screen that decrements the counter by 1 but prevents it from going below 0.
5. **Reset Button**: A third floating action button (FAB) located below the counter display that resets the counter to 0.
6. **Bonus Feature**: A snackbar appears when the counter reaches 10, showing the message: "You’ve reached 10 clicks!"

## Dependencies

To run this app, make sure you have the following:

- **Flutter SDK** (latest version)
- **Dart** (latest version)

## Usage

Once the app is running, you can:

- **Increment** the counter by pressing the floating action button on the bottom right.
- **Decrement** the counter using the button on the bottom left, but the counter won’t go below 0.
- **Reset** the counter to 0 by pressing the reset button.

>[!NOTE]
>If the counter reaches **10**, a **snackbar** message will appear notifying you that you’ve reached 10 clicks.

## Installation

To install and run this Flutter app locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yehiarasheed/flutter_counter_app.git
    ```

2. Change into the project directory:

    ```bash
    cd flutter_counter_app
    ```

3. Install the required dependencies:

    ```bash
    flutter pub get
    ```

4. Run the app on your connected device or emulator:

    ```bash
    flutter run
    ```
I advise the use of an emulator or connected device for better visuals.

---
