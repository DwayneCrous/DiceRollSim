# 🎲 Dice Simulation Application

A Java-based dice roll simulator that calculates and displays the frequencies, fractions, percentages, and decimal values of dice outcomes based on user-defined roll counts.

## ✨ Features

- 🎲 Simulate rolling a six-sided die multiple times.
- 📊 Automatically calculate and display:
  - 📈 Frequencies of each outcome.
  - ➗ Fractional representation of frequencies.
  - 📉 Percentages of each outcome.
  - 🔢 Decimal values of each outcome.
- 🧹 Clear all fields with the click of a button.

## 🖥️ Application Overview

### `btnProcessActionPerformed`

This method:

1. 📥 Reads the total number of dice rolls from the user.
2. 🎲 Simulates the dice rolls using a random number generator.
3. 📋 Calculates the frequencies for each dice face (1 through 6).
4. 🧮 Computes:
   - ➗ Fractions (e.g., `5/100`)
   - 📉 Percentages (e.g., `5%`)
   - 🔢 Decimal values (e.g., `0.05`)
5. 🔄 Updates the GUI with the results.

### `btnClearActionPerformed`

This method:

1. 🧹 Clears all input and output fields in the application.
