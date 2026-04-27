# Unit Converter – JavaFX Desktop Application

A desktop unit conversion application developed in **Java** using **JavaFX** and **FXML**.  
The project was designed with an object-oriented architecture to support multiple measurement categories, dynamic unit selection, reusable conversion logic, and a responsive graphical interface.

---

## Features

- Convert values between multiple unit systems
- Clean JavaFX desktop interface
- Multiple measurement categories:
  - Length
  - Area
  - Volume
  - Weight / Mass
  - Speed
  - Pressure
  - Temperature
  - Time
  - Direction
- Dynamic source / destination unit selection
- Swap source and destination units
- Unit sorting options
- Reusable conversion engine based on SI normalization
- Custom icons and UI components
- Logging system integration

---

## Technologies Used

- **Java**
- **JavaFX**
- **FXML**
- Object-Oriented Programming
- Design Patterns:
  - Factory Pattern
  - Flyweight Pattern
- Java Properties / Bindings

---

## Project Structure

```text
src/
├── application/
│   ├── Main.java
│   ├── Controller.java
│   ├── Converter.java
│   └── ConverterFrame.fxml
│
├── measures/
│   └── MeasureType.java
│
├── measures/units/
│   ├── Unit.java
│   ├── BaseNumericUnit.java
│   ├── DerivedNumericUnit.java
│   ├── BaseSymbolicUnit.java
│   ├── DecomposedUnit.java
│   └── UnitsFactory.java
│
├── application/cells/
├── utils/
└── logger/
