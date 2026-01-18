# Text Analyzer

A simple Python utility for analyzing text files and extracting statistical insights about word frequency and document composition.

## Features

- **Line Counting**: Count total lines in a text file
- **Word Counting**: Count total words in a text file
- **Word Frequency Analysis**: Identify the most common words and their frequencies
- **Average Metrics**: Calculate average words per line
- **Top N Words**: Extract and display the top N most frequent words with counts

## Installation

### Prerequisites

- Python 3.x

### Setup

1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the analyzer on a text file:

```bash
python runner.py
```

By default, the program analyzes `testt.txt` and displays the top 10 most common words.

### Customization

Edit `runner.py` to change:
- **File path**: Modify the `fname` variable to analyze a different file
- **Top N words**: Change the `top_N` variable to display more or fewer top words

Example:
```python
fname = "your_file.txt"
top_N = 20
```

## Output

The program displays:
- Total line count
- Total word count
- Average words per line
- A table of the top N words with their frequencies

Example output:
```
Lines: 150
Words: 2500
Average Words Per Line: 16.67
|--------------|
Top 10 Words:

The ------------ 145
And ------------ 89
That ----------- 76
```

## Project Structure

- `runner.py` - Main entry point
- `helpers.py` - Core `TextAnalyzer` class with analysis methods
- `requirements.txt` - Project dependencies

## License

This project is provided as-is for educational purposes.
