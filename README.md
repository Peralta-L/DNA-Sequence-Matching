# DNA Sequence Matching

This Python program identifies a person based on DNA — by comparing a sequence of repeating substrings (STRs) from a `.txt` file against a database of known individuals stored in a `.csv` file.

Inspired by the popular [CS50: Introduction to Computer Science](https://cs50.harvard.edu/) problem set, this project helps you learn how to handle files, dictionaries, and string manipulation.
For education only.

---

## What It Does

1. Reads a CSV file containing names and counts of STRs.
2. Reads a DNA sequence file (as a string).
3. Finds the **longest match** of each STR in the sequence.
4. Compares these counts with the database to identify the person.

---

## How to Run

### Requirements

- Python 3
- Command line / terminal

### Usage

bash
python dna.py data.csv sequence.txt
data.csv: contains names and STR counts

sequence.txt: contains the DNA sequence to analyze

Example:

bash
python dna.py small.csv sequence.txt
Lavender
Project Structure
File	Description
dna.py	Main Python script for STR matching
data.csv	Sample DNA profiles of individuals
sequence.txt	DNA string to analyze
README.md	Instructions and project overview
 Concepts Practiced
File I/O with csv and plain text

Command-line argument handling (sys.argv)

Dictionaries for frequency analysis

Sliding window and substring matching

Algorithmic thinking and loop optimization

Acknowledgements
This project was originally developed for the CS50 course at Harvard University. Grateful to CS50’s team for teaching core programming concepts through meaningful, real-world-inspired problems.
