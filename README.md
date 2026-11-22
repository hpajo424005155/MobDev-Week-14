# Week 14 Activity: Two-Screen Flutter Static UI

**Name:** Harvey Pajo
**Section:** BSIT 3.2
**Date:** November 20, 2026
**Course:** PC16 – Mobile Development with Lab

## Project Overview
This project is a Flutter application that demonstrates the creation of a two-screen static user interface based on my Week 2 Figma design. It uses Material Design principles and standard Flutter widgets to replicate the layout.

## Features Implemented (Based on Rubric)
1. **Two Screens:** 
   - `NewOrderScreen` (Frame 1)
   - `OrderSummaryScreen` (Frame 2)
2. **Widget Composition:** Uses `Scaffold`, `AppBar`, `Row`, `Column`, `Expanded`, and `Container` for layouts.
3. **Stack and Positioned:** The food cards use a `Stack` with a `Positioned` widget to display a red "NEW" badge overlapping the food image (with `clipBehavior: Clip.none`).
4. **Image Asset:** Uses `Image.asset` to display local images (`burger.png`, `pizza.png`, `iced_tea.png`, `soft_drinks.png`) with `BoxFit.cover`.
5. **Sizing and Spacing:** Utilizes `Padding`, `SizedBox`, and `Expanded` to ensure a clean layout without overflow on mobile screens.
6. **ThemeData:** Both screens share a consistent color theme defined in `MaterialApp`.

## How to Run
1. Make sure you have the Flutter SDK installed.
2. Open the terminal in the project folder.
3. Run the following command to get the dependencies:
   ```bash
   flutter pub get
