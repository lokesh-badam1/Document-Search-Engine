
# Document Search Engine

This project implements a **Document Search Engine** using **TF-IDF (Term Frequency-Inverse Document Frequency)** and **Cosine Similarity** to identify the most relevant documents based on a user's query.

## Features

- Calculates the relevance of documents using TF-IDF vectorization.
- Measures similarity between the query and documents using cosine similarity.
- Allows users to add their own documents for search.
- Outputs the most relevant document(s) for a given query.

## Installation

1. Clone the repository or download the project files.

2. Ensure you have Python 3.x installed on your system.

## Usage

### Adding Documents
- Place your documents (text files) in the `stories/` directory.
- Alternatively, provide a custom path to the directory containing your documents in the code.

### Running the Search Engine
1. Open the `NLP Project (Final).ipynb` file using Jupyter Notebook.
2. Execute the cells step-by-step to initialize and run the search engine.
3. Input a search query when prompted.
4. The system will output the most relevant document(s) along with their similarity scores.

### Example
If your `stories/` directory contains:
- `doc1.txt` (content: *"The quick brown fox jumps over the lazy dog."*)
- `doc2.txt` (content: *"A journey of a thousand miles begins with a single step."*)

Query: `"fox jumps"`  
Output: The system will identify `doc1.txt` as the most relevant document.

## Directory Structure

```
.
├── stories/            # Directory to store your documents
├── NLP Project (Final).ipynb  # Jupyter Notebook for the project
└── README.md           # Project documentation
```

## Dependencies

The project relies on the following Python libraries:
- **Numpy**
- **Pandas**
- **NLTK**
- **Scikit-learn**



Happy Searching! 🚀
