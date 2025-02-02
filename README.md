# Text Summarization and Evaluation using ROUGE & TOPSIS

## Overview

This project performs text summarization using a pretrained transformer model and evaluates the generated summaries using the ROUGE metric. The summaries are then ranked using the TOPSIS method, a multi-criteria decision-making approach.

## Features

- **Text Summarization**: Uses the `transformers` library to generate multiple summaries.
- **ROUGE Score Evaluation**: Computes `ROUGE-1`, `ROUGE-2`, and `ROUGE-L` scores to compare the generated summaries with a reference summary.
- **TOPSIS Ranking**: Ranks the summaries based on their similarity to an ideal summary.
- **Visualization**: Uses `matplotlib` and `seaborn` to plot the TOPSIS scores.

## Requirements

Ensure you have the following Python packages installed:

```sh
pip install numpy matplotlib transformers rouge-score seaborn
```

If you're using Google Colab, you may also need to run:

```sh
!pip install rouge-score
```

## Usage

1. **Initialize the summarization model**: Loads a pretrained transformer model.
2. **Generate summaries**: Creates multiple summaries of the input text.
3. **Evaluate summaries**: Uses ROUGE metrics to compare them against a reference summary.
4. **Normalize scores & apply TOPSIS**: Determines the best summary using a decision-making algorithm.
5. **Visualize results**: Displays the ranking of summaries using a bar plot.

## Running the Code

Simply execute the Python script in a Jupyter Notebook, Google Colab, or a local Python environment.

```python
python summarization_topsis.py
```

## Output

- **Generated Summaries**: Three different summaries of the input text.
- **ROUGE Scores**: Evaluation metrics comparing summaries with the reference text.
- **TOPSIS Ranking**: A ranked list of summaries with the best one at the top.
- **Visualization**: A bar chart displaying TOPSIS scores.

## Example Output

```
Summaries Generated: ["Summary 1", "Summary 2", "Summary 3"]
ROUGE Scores (F-measure): [[0.45, 0.32, 0.50], ...]
Normalized ROUGE Scores: [[1.0, 0.89, 0.97], ...]
Ranked Summaries (0 is best): [1, 0, 2]
```

## License

This project is open-source and available under the MIT License.

## Author

Sameer Garg

# Text Summarization and Evaluation using ROUGE & TOPSIS

## Overview

This project performs text summarization using a pretrained transformer model and evaluates the generated summaries using the ROUGE metric. The summaries are then ranked using the TOPSIS method, a multi-criteria decision-making approach.

## Features

- **Text Summarization**: Uses the `transformers` library to generate multiple summaries.
- **ROUGE Score Evaluation**: Computes `ROUGE-1`, `ROUGE-2`, and `ROUGE-L` scores to compare the generated summaries with a reference summary.
- **TOPSIS Ranking**: Ranks the summaries based on their similarity to an ideal summary.
- **Visualization**: Uses `matplotlib` and `seaborn` to plot the TOPSIS scores.

## Requirements

Ensure you have the following Python packages installed:

```sh
pip install numpy matplotlib transformers rouge-score seaborn
```

If you're using Google Colab, you may also need to run:

```sh
!pip install rouge-score
```

## Usage

1. **Initialize the summarization model**: Loads a pretrained transformer model.
2. **Generate summaries**: Creates multiple summaries of the input text.
3. **Evaluate summaries**: Uses ROUGE metrics to compare them against a reference summary.
4. **Normalize scores & apply TOPSIS**: Determines the best summary using a decision-making algorithm.
5. **Visualize results**: Displays the ranking of summaries using a bar plot.

## Running the Code

Simply execute the Python script in a Jupyter Notebook, Google Colab, or a local Python environment.

```python
python summarization_topsis.py
```

## Output

- **Generated Summaries**: Three different summaries of the input text.
- **ROUGE Scores**: Evaluation metrics comparing summaries with the reference text.
- **TOPSIS Ranking**: A ranked list of summaries with the best one at the top.
- **Visualization**: A bar chart displaying TOPSIS scores.

## Example Output

```
Summaries Generated: ["Summary 1", "Summary 2", "Summary 3"]
ROUGE Scores (F-measure): [[0.45, 0.32, 0.50], ...]
Normalized ROUGE Scores: [[1.0, 0.89, 0.97], ...]
Ranked Summaries (0 is best): [1, 0, 2]
```

## License

This project is open-source and available under the MIT License.

## Author

Sameer Garg

