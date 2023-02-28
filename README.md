# DNA Matching Program
This program takes a CSV file containing a DNA database and a text file containing a DNA sequence as inputs, and searches the database to determine if the sequence matches any individuals in the database.

## Requirements
Python 3.6 or later
CSV file containing DNA database
Text file containing DNA sequence

## Usage
To run the program, use the following command:
python dna.py database.csv sequence.txt

## Output
If a match is found in the database, the program will output the name of the matched individual. If no match is found, the program will output "No match".

## How it Works
The program works by finding the longest run of repeating DNA sequences (called short tandem repeats, or STRs) in the DNA sequence file. 
It then compares the number of repeats of each STR in the DNA database to the number of repeats found in the DNA sequence file. 
If the number of repeats matches for all STRs, the program outputs the name of the matched individual

