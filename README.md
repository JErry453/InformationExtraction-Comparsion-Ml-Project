# Information Extraction & Comparison Project

This project is designed to perform information extraction and comparison between two textual paragraphs. It leverages Natural Language Processing (NLP) techniques to preprocess the text, compare sentences, and analyze sentiments to determine which entity (described in the texts) is better based on numerical data and sentiment analysis.

## Features

- **Preprocessing**: Tokenizes, lemmatizes, and removes stop words from the input text.
- **Sentence Comparison**: Compares sentences from two paragraphs based on their content similarity.
- **Numerical Data Extraction**: Identifies and compares numerical data present in sentences.
- **Sentiment Analysis**: Uses sentiment analysis to determine the positivity or negativity of sentences.
- **Final Decision**: Compares entities in two texts to provide a final decision on which entity is better.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/InformationExtraction-Comparison-Ml-Project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd InformationExtraction-Comparison-Ml-Project
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the necessary NLTK data:
    ```python
    import nltk
    nltk.download('vader_lexicon')
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook InformationExtraction&Comparison.ipynb
    ```

2. Run the notebook cells to execute the code. You can modify the input text within the cells to test different scenarios.

## Project Structure

- **InformationExtraction&Comparison.ipynb**: The main Jupyter Notebook file containing all the code for the project.
- **requirements.txt**: A file listing all the necessary Python packages for the project.

## Libraries Used

- `spacy`: For text processing, tokenization, and lemmatization.
- `numpy`: For numerical operations and matrix manipulations.
- `scikit-learn`: For calculating cosine similarity.
- `nltk`: For sentiment analysis using the VADER lexicon.
- `pandas`: For data display and manipulation.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
