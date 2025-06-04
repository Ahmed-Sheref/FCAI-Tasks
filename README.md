# 🎓 FCai Programming Assignment – Term 1

## 👨‍💻 Student Info
- **Name:** Ahmed Sheref Sayed Ahmed  
- **ID:** 20230542  
- **TA Name:** Mohamed Elramly  
- **Submission Date:** 10 Oct 2024  

---

## 📦 Project List

| Task | Title                                  | Folder Name             |
|------|----------------------------------------|--------------------------|
| 1    | Multi-Tool Console Application         | `A1_T1_NULL_20230542`    |
| 2    | Terminal-Based UI (Calculator + Cipher)| `A1_T2_NULL_20230542`    |
| 3    | OOP-Based Simple Game                  | `A1_T3_NULL_20230542`    |

---

## 🧩 Task 1 – Multi-Tool Console Application

# StringSet Project

## Overview
This project provides a C++ implementation of a `StringSet` class designed to manage collections of words from text input or files. It supports basic set operations such as union and intersection, word addition/removal, and computes similarity between two sets based on their content.

---

## Features

- **Load words from a file**: Reads text from a specified file, processes it by extracting alphabetic words, converting them to lowercase, and storing them in the document set (`D`).
- **Load words from a text string**: Parses an input string similarly to create a query set (`Q`).
- **Add/Remove words**: Allows dynamic modification of the query set with new or removed words.
- **Clear query set**: Empties the query set.
- **Set operations**:
  - **Union (`+`)**: Combines two `StringSet` objects' query sets, eliminating duplicates.
  - **Intersection (`*`)**: Finds common words between two `StringSet` objects' query sets.
- **Similarity computation**: Calculates a similarity score between the document set (`D`) and query set (`Q`) based on the cosine similarity formula applied to the presence of unique words.
- **Display functionality**: Shows the current query set in a neat, tabular format with indices and words.
- **Helper utilities**: Helper class for file handling, character checks, and word extraction.

---

## Project Structure

- `main.cpp`: Contains the `StringSet` class, helper classes, and `ahmedsheref2288` function demonstrating the usage.
- `test.txt`: Sample input file containing text data (make sure to create this in your project folder for testing).

---
🧮 Task 2 – Terminal UI: Calculator & Caesar Cipher
📁 Folder: A1_T2_NULL_20230542

✨ Features
✅ Terminal Calculator (Basic Arithmetic)

✅ Caesar Cipher Encryptor (User-defined key)

🎨 UI Elements
ASCII UI layout

Colored terminal output (if supported)

🚀 How to Compile & Run
bash
Copy
Edit
cd A1_T2_NULL_20230542
g++ -std=c++11 -o Task2 main.cpp
./Task2
🎮 Task 3 – Object-Oriented Game
📁 Folder: A1_T3_NULL_20230542

🧱 OOP Features
✅ Class-based structure with inheritance

✅ Abstraction & Polymorphism

✅ Clean encapsulated logic

🚀 How to Compile & Run
bash
Copy
Edit
cd A1_T3_NULL_20230542
g++ -std=c++11 -o Task3 main.cpp
./Task3
# Word Frequency Counter

## Overview

This C++ program reads a text file and calculates the frequency of each unique word in the file. It processes the text by removing punctuation, converting words to lowercase for case-insensitive comparison, and ignoring numeric strings (words that consist only of digits). The results are displayed in a neatly formatted table showing each word alongside its frequency count.

---

## Features

- Prompts the user to enter the filename of the text file to analyze.
- Opens and reads the file word by word.
- Cleans each word by:
  - Removing punctuation characters.
  - Converting all letters to lowercase to ensure case-insensitive counting.
- Ignores words that contain only numbers (e.g., "12345").
- Uses a `map<string, int>` to count and store the frequency of each word.
- Dynamically adjusts the output table width according to the longest word found.
- Displays a formatted table of words and their corresponding frequencies.

 Modular, clean code with comments

 Working executables (tested)

 Submitted before deadline
