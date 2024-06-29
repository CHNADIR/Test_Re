# Word Occurrence Counter

## Overview

This Python script counts the occurrences of a specified word (case insensitive) in a given text. It includes functionality for unit testing and profiling to analyze performance.

## Features

**Count occurrences**: Counts occurrences of a word or phrase in a given text.

**Case insensitive**: The search is case insensitive.

**Unit tests**: Includes tests to validate the functionality.

**Profiling**: Uses cProfile for performance analysis.

## Usage

### Counting Occurrences

The main function to count occurrences is count_occurrences_in_text(word, text). It takes two parameters:

  -**word**: The word or phrase to search for.
  
  -**text**: The text in which to search.
  
### Running Tests

To run the unit tests, use the following command:

`python -m pytest a9number_v3.py`

### Profiling

To see the profiling results, run the tests with the -s option:

`python -m pytest a9number_v3.py -s`

### Functions

`count_occurrences_in_text(word, text)`

Returns the number of occurrences of the passed word (case insensitive) in the text.


### Requirements

  -Python 3.x

  -pytest

### License
This project is licensed under the MIT License - see the LICENSE file for details.
