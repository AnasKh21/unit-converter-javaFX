# Unit Converter – JavaFX Desktop Application

A desktop unit conversion application built in **Java** with **JavaFX** and **FXML**.  
The project focuses on clean object-oriented design, reusable conversion logic, and a responsive graphical interface.

---

## Features

- Convert values across multiple measurement systems
- Modern JavaFX desktop interface
- Dynamic source / target unit selection
- Swap source and destination units
- Unit sorting options
- Reusable conversion engine based on SI normalization
- Logging support

### Supported Categories

- Length
- Area
- Volume
- Weight / Mass
- Speed
- Pressure
- Temperature
- Time
- Direction

---

## Technologies

- Java
- JavaFX
- FXML
- Java Properties / Bindings
- Object-Oriented Programming

### Design Patterns

- Factory Pattern
- Flyweight Pattern

---

## Run the Project

### Option 1 — IDE (Recommended)

Use Eclipse IDE or IntelliJ IDEA.

1. Open the project folder  
2. Select JDK 11+  
3. Add JavaFX SDK libraries if needed  
4. Run `src/application/Main.java`

---

### Option 2 — Command Line

```bash
javac --module-path /path/to/javafx-sdk/lib \
--add-modules javafx.controls,javafx.fxml \
-d bin $(find src -name "*.java")

cp -r src/icons bin/
cp src/application/*.fxml bin/application/
cp src/application/*.css bin/application/
cp src/application/cells/*.fxml bin/application/cells/

java --module-path /path/to/javafx-sdk/lib \
--add-modules javafx.controls,javafx.fxml \
-cp bin application.Main
