# Codsoft-2-WordCounter

A Java program that counts the number of words, unique words, and word frequency in a given text.

## Introduction

"Word Counter" is a simple Java program that allows users to input a text and provides various statistics related to the words in the text. It counts the total number of words, the number of unique words, and the frequency of each word in the text.

## Features

- Counts the total number of words in the given text.
- Calculates the number of unique words in the text.
- Displays the frequency of each word in the text.

## How to Use

1. Clone or download this repository to your local machine.

2. Open a terminal (command prompt) and navigate to the project directory.

3. Compile the Java source code:
   ```
   javac WordCounter.java
   ```

4. Run the program:
   ```
   java WordCounter
   ```

5. Follow the on-screen instructions to enter the text for analysis.

## Example

Suppose you enter the following text:
```
The quick brown fox jumps over the lazy dog. The dog barks loudly as the fox runs away.
```

The program will provide the following output:
```
Enter the text: The quick brown fox jumps over the lazy dog. The dog barks loudly as the fox runs away.
Number of words in the text: 21
Number of unique words in the text: 15
Word frequency:
the: 2
quick: 1
brown: 1
fox: 2
jumps: 1
over: 1
lazy: 1
dog: 2
barks: 1
loudly: 1
as: 1
runs: 1
away: 1
```

## How it Works

The program takes the input text and performs the following steps:

1. Converts the text to lowercase and removes punctuation marks (except for apostrophes in words like "can't") to clean the text.

2. Counts the total number of words in the cleaned text by splitting it based on whitespace.

3. Calculates the number of unique words in the text by using a HashMap to store word frequencies.

4. Displays the frequency of each word in the text using the same HashMap.


Enjoy using the Word Counter! ![Screenshot 2023-07-25 153348](https://github.com/deepaktallapudi/Codsoft-2-WordCounter/assets/103422044/440f8e5d-684d-457b-b3f5-0d3670124d44)
