# Unscramble Game

## Overview

Unscramble Game is a simple word puzzle Android application built using **Kotlin** and **Jetpack Compose**. The game presents scrambled words to the user, who must guess the correct word. The application demonstrates modern Android development practices such as **State Management**, **ViewModel Architecture**, and **UI State Handling**.

The game consists of **10 rounds**, where each correct answer awards **20 points**. A new set of randomly selected words is generated every time a new game starts, making each playthrough unique and engaging.

---

## Features

* Displays scrambled words one at a time.
* Random word selection for every game.
* Score tracking throughout the game.
* 10-word gameplay session.
* Skip word functionality.
* Play Again option after game completion.
* Built using Jetpack Compose UI.
* State-driven UI updates.

---

## How to Play

1. Read the scrambled word displayed on the screen.
2. Enter your guess in the text field.
3. Press **Submit** to check your answer.
4. Earn **20 points** for every correct guess.
5. Use **Skip** if you want to move to the next word.
6. Continue until all **10 words** have been attempted.
7. At the end of the game, view your final score.
8. Select **Play Again** to start a new game with a fresh set of words.

---

## Tech Stack

* Kotlin
* Jetpack Compose
* Android Studio
* ViewModel
* StateFlow / MutableStateFlow
* Material Design Components

---

## Project Structure

### UI Layer

Responsible for displaying data to the user and handling user interactions.

### ViewModel Layer

Manages application data and business logic while surviving configuration changes.

### Data Layer

Stores and manages the word list, score information, and game-related data.

---

## Key Learnings

### 1. ViewModel

* Managing UI-related data separately from UI components.
* Preserving data during configuration changes.
* Keeping business logic outside composables.

### 2. UI State Management

* Creating and updating UI state objects.
* Observing state changes from the UI.
* Building reactive user interfaces.

### 3. State Holders

* Using dedicated classes to manage application state.
* Centralizing data updates.
* Improving maintainability and scalability.

### 4. StateFlow

* Exposing immutable state to the UI.
* Updating state safely within the ViewModel.
* Automatically triggering recomposition when data changes.

### 5. Jetpack Compose

* Building declarative user interfaces.
* Managing recomposition efficiently.
* Handling user interactions through state updates.

### 6. Separation of Concerns

* Organizing code into different classes and layers.
* Separating UI, data, and business logic.
* Writing cleaner and more maintainable code.

### 7. Data Flow in Android Apps

* Understanding how data moves from the ViewModel to the UI.
* Managing user actions and state updates.
* Maintaining a single source of truth.

### 8. Game State Handling

* Tracking scores and word counts.
* Managing game completion conditions.
* Resetting and restarting game data.
