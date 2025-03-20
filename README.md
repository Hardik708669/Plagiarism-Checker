# Plagiarism Checker

## Overview
This project is a text-based plagiarism detection system that analyzes similarity between multiple text files using Natural Language Processing (NLP). It utilizes TF-IDF vectorization and cosine similarity to measure the closeness between documents.

## Features
- **Automatic Text Comparison:** Reads multiple `.txt` files and compares their similarity.
- **Plagiarism Detection:** Uses `TF-IDF` and `cosine similarity` to find similar content.
- **Result Output:** Displays the similarity score for each document pair.

## Technologies Used
- `Scikit-learn` for machine learning and NLP processing
- `TF-IDF Vectorization` for text analysis
- `Cosine Similarity` for document comparison

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/plagiarism-checker.git
   cd plagiarism-checker
   ```
2. Install dependencies:
   ```sh
   pip install scikit-learn
   ```
3. Place text files (`.txt`) in the project directory.
4. Run the application:
   ```sh
   python app.py
   ```

## Usage
- The script will scan all `.txt` files in the directory.
- It will compute similarity scores and display potential plagiarism cases.

## License
This project is open-source and available under the MIT License.

