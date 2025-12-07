## 🚀 Maths Wars: The Time-Warp Math Quiz

An engaging, fast-paced Android quiz game designed to test and sharpen mathematical skills from basic arithmetic to challenging roots and radicals. Choose your difficulty, race against the 10-second clock, and prove your mastery to become a Math Jedi!

### ✨ Key Features

* **Three Difficulty Levels**:
    * **Easy:** Addition and Subtraction only.
    * **Medium:** Includes Multiplication and Division.
    * **Hard:** Introduces Square Roots and Nth Radicals.
* **Timed Challenge:** 10-second countdown timer for each question.
* **Score and Rank Tracking:** Persistently tracks the high score and assigns ranks (Padawan, Knight, Jedi) based on performance.
* **Feedback System:** Provides sound effects (correct/wrong) and haptic feedback (vibration) for correct and incorrect answers.
* **User Settings:** Dedicated settings screen to enable/disable sound.

### 💻 Tech Stack

This project is a native Android application built using the following technologies:

| Category | Technology | Notes |
| :--- | :--- | :--- |
| **Platform** | Android SDK (API 35) | Minimum SDK 24 |
| **Language** | Java 11 | Core logic implemented in Java Activities. |
| **Build System** | Gradle (Kotlin DSL) | Uses `gradle-8.10.2`. |
| **UI** | Android XML Layouts | Custom styles for buttons and backgrounds. |
| **Media** | SoundPool API | Used for playing `correct.mp3` and `wrong.mp3` feedback sounds. |

### ⚙️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

#### Prerequisites

* **Android Studio:** Latest version (recommended).
* **Java Development Kit (JDK):** Version 11 or higher.

#### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/its-ousama/math-wars-android
    ```
2.  **Open in Android Studio:**
    * Start Android Studio.
    * Select `File` -> `Open...` and navigate to the root directory of the cloned project (`math-wars-android`).
3.  **Sync Gradle:**
    * Android Studio will automatically prompt you to sync the project. Click `Sync Now`.
4.  **Run the Application:**
    * Select an emulator or physical device (API 24 or newer).
    * Click the **Run** button (green arrow) in the toolbar.

### 🎮 Usage

1.  **Start Quiz:** On the main screen, tap the "Start Quiz" button.
2.  **Select Difficulty:** Choose one of the three levels (Easy, Medium, Hard).
3.  **Answer Questions:** Select the correct answer from the four options before the 10-second timer runs out.
4.  **View Results:** When the game ends (by a wrong answer or running out of time), your final score and rank will be displayed, along with the all-time high score.
