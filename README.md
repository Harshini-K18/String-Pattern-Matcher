# String-Pattern-Matcher

String-Pattern-Matcher-GUI is a Java-based application that demonstrates the Brute Force and Horspool string matching algorithms in a user-friendly graphical interface. This tool allows users to load a text file, search for a specified pattern, and replace it with a new string. The application is built using Java Swing and provides a detailed view of the matching process step-by-step.

## Prerequisites

- **Java Development Kit (JDK)**: Version 8 or higher is required to compile and run this application.
- **IDE** (Optional): An IDE like IntelliJ IDEA, Eclipse, or NetBeans is recommended for running and testing the application.

## How to Use

1. **Clone the Repository**

2. **Compile the Application**:

3. **Run the Application**:
  
4. **Use the GUI**:
   - Load a text file using the file chooser.
   - Enter the pattern to search and the string to replace it with.
   - Select the desired algorithm (Brute Force or Horspool).
   - View the step-by-step matching process in the display area.
   - Save the modified file 

### Brute Force Algorithm

The brute force algorithm searches for a pattern in the text by checking every possible position in the text for a match. It compares the pattern to the text character by character, which makes it straightforward but potentially slow for large texts.

### Horspool Algorithm

The Horspool algorithm improves the efficiency of pattern searching by using a heuristic to skip unnecessary comparisons. It precomputes a shift table based on the pattern and uses it to jump over sections of the text that cannot contain the pattern.
