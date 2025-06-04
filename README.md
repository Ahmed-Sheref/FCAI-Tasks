# 🎓 FCai Programming Assignment – Term 1

## 👨‍💻 Student Information  
- **Name:** Ahmed Sheref Sayed Ahmed  
- **ID:** 20230542  
- **TA Name:** Mohamed Elramly  
- **Submission Date:** 10 Oct 2024  

---

## 📦 Project List

| Task | Title                                   | Folder Name             |
|-------|----------------------------------------|------------------------|
| 1     | Multi-Tool Console Application          | `A1_T1_NULL_20230542`  |
| 2     | Terminal-Based UI (Calculator + Cipher) | `A1_T2_NULL_20230542`  |
| 3     | OOP-Based Simple Game                   | `A1_T3_NULL_20230542`  |

---

## 🧩 Task 1 – Multi-Tool Console Application

### StringSet Project

#### Overview  
This project implements a C++ `StringSet` class to manage collections of words extracted from text or files. It supports fundamental set operations, word management, and similarity measurement between sets.

#### Features  
- **Load words from a file:** Reads text from a file, extracts alphabetic words, converts them to lowercase, and stores them in a document set (`D`).  
- **Load words from a string:** Processes input strings to create a query set (`Q`) in the same manner.  
- **Add/Remove words:** Allows dynamic modification of the query set.  
- **Clear query set:** Empties the current query set.  
- **Set operations:**  
  - **Union (`+`)**: Combines query sets from two `StringSet` instances without duplicates.  
  - **Intersection (`*`)**: Finds common words between two query sets.  
- **Similarity calculation:** Computes a cosine similarity score between document and query sets based on unique word presence.  
- **Display:** Neatly prints the query set with indices for easy viewing.  
- **Helper utilities:** Includes helper classes for file handling, character checks, and word extraction.  

#### Project Files  
- `main.cpp`: Contains the `StringSet` implementation and a demonstration function `ahmedsheref2288`.  
- `test.txt`: Sample text file to test file loading features (ensure this file is present in the project directory).

---

## 🧮 Task 2 – Terminal UI: Calculator & Caesar Cipher  
**Folder:** `A1_T2_NULL_20230542`  

#### Features  
- Basic terminal calculator supporting addition, subtraction, multiplication, and division.  
- Caesar cipher encryptor with user-defined key.  
- Simple ASCII UI layout with colored terminal output (if supported).  

#### Compile & Run  
```bash
cd A1_T2_NULL_20230542
g++ -std=c++11 -o Task2 main.cpp
./Task2
 Task 3 – Object-Oriented Game
Folder: A1_T3_NULL_20230542

Features
Clean, class-based structure with inheritance.

Implements abstraction and polymorphism principles.

Well-encapsulated game logic.

Compile & Run
bash
Copy
Edit
cd A1_T3_NULL_20230542
g++ -std=c++11 -o Task3 main.cpp
./Task3
Word Frequency Counter
Overview
This C++ program reads a text file and calculates the frequency of each unique word. It processes the text by removing punctuation, converting words to lowercase (case-insensitive counting), and ignoring numeric-only strings. The results are displayed in a clean table format.

Features
Prompts user for the filename to analyze.

Reads the file word-by-word, cleaning and normalizing the input.

Removes punctuation characters from words.

Converts all words to lowercase for case-insensitive frequency counting.

Ignores words composed entirely of digits.

Uses std::map<std::string, int> to count frequencies of unique words.

Dynamically adjusts the output table width to fit the longest word.

Displays a formatted table showing each word and its frequency count.

Additional Notes
The code is modular and clean for easy maintenance.

The program has been tested and produces working executables.

Submitted before the deadline.
