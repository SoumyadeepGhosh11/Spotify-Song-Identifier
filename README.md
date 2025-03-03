# Spotify Song Identifier

## Overview
This project is a simple song identifier that uses a snippet of lyrics to find the corresponding song and artist. It leverages the **Spotify Million Song Dataset** and uses **TF-IDF Vectorization** along with **Cosine Similarity** to match the input lyrics with the dataset.

## Features
- **Lyrics-based Search**: Enter a snippet of song lyrics to identify the song and artist.
- **TF-IDF Vectorization**: Uses Term Frequency-Inverse Document Frequency (TF-IDF) to convert lyrics into a numerical format for comparison.
- **Cosine Similarity**: Measures the similarity between the input lyrics and the dataset to find the best match.
- **Gradio Interface**: Provides a user-friendly web interface for easy interaction.

## Requirements
To run this project, you need the following Python libraries:
- `pandas`
- `scikit-learn`
- `gradio`
- `re` (built-in)

You can install the required libraries using pip:
```bash
pip install pandas scikit-learn gradio
