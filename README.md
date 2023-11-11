# Markov Algorithm for Character Counting

This repository contains a C++ program that uses a [Markov algorithm](https://en.wikipedia.org/wiki/Markov_algorithm) to find out if there are more "a" or "b" characters in a word from the {a, b} alphabet (`./markov.cpp`). The result is a word with extra characters of the greater number.

Additionally, the repository includes a Russian-language PDF report for the corresponding assignment in the "Discrete Mathematics" course at the Polytechnic University of Saint Petersburg (`./report.pdf`).

## Usage

1. Clone the repository: `git clone https://github.com/seigtm/markov.git`
2. Compile and run the program.
3. Follow the on-screen instructions to input the word.
4. The program will output the original word, apply the Markov algorithm, and display the result.

## Markov Algorithm

The algorithm is based on the following rules:

- **Rule 1**: Replace "**ab**" with an empty string.
- **Rule 2**: Replace "**ba**" with an empty string.

## Example

For the word "**abaabaab**," the result is "**aa**" since there are 5 "**a**" and 3 "**b**", resulting in an excess of 2 "**a**" over "**b**".

## Verification

The correctness of the algorithm is verified by comparing the obtained result with the expected result.
