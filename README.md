# Word Probability Calculator

This Python program calculates the likelihood of a word being accurate based on a provided text file. Unlike automatic correction tools, it concentrates on evaluating word probabilities without making corrections.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/YaminThiriWai/word-probability-calculator
   cd word-probability-calculator
   ```

2. **Run the Program:**

   ```bash
   python probability_calculator.py
   ```

3. **Example Usage:**

   ```python
   result = my_autocorrect('examplle')
   print(result)
   ```

## Functionality

The program follows these key functionalities:

- Reads a text file.
- Tokenizes the words for analysis.
- Calculates probabilities for each word in the vocabulary.
- While it doesn't automatically correct words, it can suggest words with higher probabilities.

## Dependencies

- nltk
- pandas
- numpy
- textdistance

## Notes

- Ensure that the required Python libraries are installed before running the script.

- If you encounter any issues or have questions, feel free to open an issue on GitHub.
