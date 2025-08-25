# Learner Task

This is a simple Java application that models a `Learner` object and calculates their final mark based on assignment, test, and exam scores. 
The program uses a graphical user interface (GUI) via `JOptionPane` for user input and output.

## Features

* Represents a learner with full name, subject, and marks for assignment, test, and exam.
* Calculates the final mark as the average of the three components.
* Uses `JOptionPane` dialogs for input and output.
* Encapsulates data using private fields and getter/setter methods.

## Structure

This project consists of two Java classes:

1. **Learner.java**

   * Contains private fields for learner details.
   * Provides constructors, getters, setters, and a method to calculate the final mark.

2. **Main.java**

   * Contains the `main` method.
   * Handles input and output using `JOptionPane`.
   * Interacts with the `Learner` class to set data and display results.

## How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Khayaguzu/learner-task.git
```

2. **Compile the Java files**

Make sure you have JDK installed. Then compile:

```bash
javac Learner.java Main.java
```

3. **Run the program**

```bash
java Main
```

## Example Workflow

1. User is prompted to enter:

   * Full name
   * Subject
   * Assignment mark
   * Test mark
   * Exam mark

2. The program calculates the final mark:

   $$
   \text{Final Mark} = \frac{\text{Assignment Mark} + \text{Test Mark} + \text{Exam Mark}}{3}
   $$

3. The final result is displayed in a dialog box.

## Notes

* The default learner details are set to "Kim James" and "Mathemtics" (note: spelling).
* No input validation is currently implemented. The user must enter valid numeric values for marks.
* Can be expanded to support multiple learners, persistence, or input validation.

---
