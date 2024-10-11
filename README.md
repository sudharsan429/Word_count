# Word_count
This project analyzes a given text to identify the most frequently occurring words, ignoring punctuation and case sensitivity. The results are dynamically displayed on a web page.

## Demo

You can view a live demo of the project [here](#).  
*(Replace the `#` with the URL to your hosted project, if available.)*

## Features

- Removes punctuation and handles case sensitivity.
- Counts the frequency of each word in the provided text.
- Displays the most common words and their counts.
- Dynamically updates the HTML content to present results.

## How It Works

1. **Input Text**: The text is defined as a string in the JavaScript code.
2. **Text Processing**:
   - Converts the text to uppercase and removes punctuation.
   - Splits the processed text into an array of words.
3. **Counting Frequencies**:
   - Iterates through the array to count the occurrences of each word.
   - Filters out words that occur more than once.
4. **Sorting and Displaying**:
   - Sorts the filtered words by frequency in descending order.
   - Displays the top three most common words along with their counts on the page.

