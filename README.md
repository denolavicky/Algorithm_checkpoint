# Sentence Analysis Algorithm

A simple, efficient pseudocode algorithm designed to process a sentence character by character to extract basic linguistic statistics.

## 📌 Overview
This algorithm reads a sequence of characters terminated by a period (`.`). It tracks three specific metrics:
1.  **Total Length:** The total number of characters in the sentence (including the period).
2.  **Word Count:** The total number of words (calculated by counting spaces + 1).
3.  **Vowel Count:** The total number of vowels ($a, e, i, o, u$), handling both uppercase and lowercase.

## 🚀 How It Works
The program initializes three counters to zero and reads the input string one character at a time.
* **While** the character is not a `.`:
    * Increment the **length** counter.
    * If the character is a **space**, increment the **word** counter.
    * If the character is a **vowel**, increment the **vowel** counter.
* **After** the loop:
    * Add 1 to the length to include the period.
    * Add 1 to the word count to include the final word before the period.

## 📊 Example Trace
**Input:** `Coding is fun.`

| Metric | Result |
| :--- | :--- |
| **Length** | 14 |
| **Words** | 3 |
| **Vowels** | 4 |

## 🛠️ Pseudocode Structure
```pascal
ALGORITHM SENTENCE
VAR
    c : CHAR
    length, vowels, words : INTEGER
BEGIN
    // Logic implementation...
END
