# Sorting Algorithm Performance Evaluator

**A Java Swing desktop application to compare the real-world performance of five classic sorting algorithms: Insertion Sort, Shell Sort, Merge Sort, Quick Sort, and Heap Sort.**

This project was developed as a group assignment to demonstrate the practical impact of algorithmic time complexity (O(n²) vs O(n log n)) on large datasets.

## Team Members
- **C. Kogulan** – 2021t01217 (Team Leader)  
  Responsible for project structure, Maven setup, GUI design, CSV file handling, numeric column detection, validation, integration, documentation, and testing.
- **M.N.A. Fathima** – 2021t1204  
  Implemented all sorting algorithms, performance timing using `System.nanoTime()`, best algorithm identification, and results export feature.

## Features
- **CSV Upload**: Load any `.csv` file from your computer.
- **Automatic Numeric Column Detection**: Only numeric columns are selectable for sorting.
- **Five Sorting Algorithms**:
  - Insertion Sort
  - Shell Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
- **Accurate Timing**: Measures execution time in milliseconds using `System.nanoTime()`.
- **Performance Comparison**: Displays execution times and highlights the **best-performing algorithm**.
- **Export Results**: Saves a beautifully formatted report (with timestamp) as a `.txt` file.

## Technologies Used
- **Language**: Java 21
- **GUI Framework**: Java Swing
- **CSV Processing**: OpenCSV 5.9
- **Build Tool**: Apache Maven
- **Packaging**: Single executable "fat" JAR (via Maven Shade Plugin)


## How to Run

### Option 1: Using Maven (Recommended)
```bash
# Navigate to project root (where pom.xml is)
cd path/to/sorting-performance-evaluator

# Clean and run
mvn clean compile exec:java
