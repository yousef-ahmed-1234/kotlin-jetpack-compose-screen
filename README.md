# Student Card Compose App

A simple Android app built with **Jetpack Compose** that demonstrates **TextFields, Cards, and live state updates**.  

---

## Features

1. **Two TextFields**
   - Input **Student Name** and **Student Grade**.

2. **Student Card**
   - Displays the entered name and grade inside a Material **Card**.
   - Shows default placeholders if fields are empty:
     - Name: `Student Name`
     - Grade: `---`

3. **Live Update**
   - The card updates **instantly** as the user types in the TextFields.

---

## How It Works

- **State Variables:**  
  `name` and `grade` are stored as `mutableStateOf("")` and observed by Compose.  

- **TextFields:**  
  Bound to state variables using `onValueChange`, so typing automatically updates the state.  

- **Card:**  
  Reads the state variables and shows their values. Uses conditional expressions to show placeholders when fields are empty.  

- **Live Update:**  
  When state changes, Compose **recomposes the card automatically**, providing real-time updates.

---

## Screenshots

*(Optional: Add screenshots here)*

---

## How to Run

1. Clone the repository.
2. Open it in **Android Studio**.
3. Build and run on an emulator or device.
4. Enter a student name and grade to see live updates in the card.

---

## Dependencies

- Jetpack Compose
- Material3
- Kotlin 1.8+  
- Android Studio Flamingo or later recommended
