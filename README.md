# Data Structure Project: The Text Processor

**Author:** Dana Nidal   

---

## Project Overview
This project is an interactive **Text Processor** designed to demonstrate the practical application of core data structures in Python. Instead of relying purely on built-in Python collections, the application actively implements and utilizes custom data structures to perform text analysis, frequency tracking, string reversal, and word sequencing.

## Data Structures & Features Implemented

The application takes a user-provided string and processes it using the following structures:

1. **Arrays & Hash Maps (Dictionaries):** * Used to map and calculate **Character Frequencies** (counting occurrences of unique letters, symbols, and spaces).
   * Used to track **Word Frequencies** (splitting the text into individual words and calculating their occurrences).
2. **Stack (LIFO - Last In, First Out):** * A custom Stack implementation used to **reverse the input text**. Characters or words are pushed onto the stack and popped off, demonstrating classic stack behavior.
3. **Queue (FIFO - First In, First Out):** * A custom Queue structure used to manage and display words sequentially in the exact order they were entered.
4. **Singly Linked List:** * Implements a custom structural node pipeline. The application populates a linked list where each word represents a node, followed by a full **Linked List Traversal** display to show the sequential list link chain (`WordA -> WordB -> WordC`).

---

## Technical Architecture
The solution is fully object-oriented and encapsulated within a primary `TextProcessor` orchestrator class, ensuring a clean separation of concerns for each standalone data structure operation.

## Libraries & Tools Used
* **Python 3**: The core programming language used to build the custom data structures.
* **Jupyter Notebook**: The interactive environment where the code is documented, executed, and tested.
