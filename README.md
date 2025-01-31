# Text Summarizer with BART

## Description
This project uses the BART (Bidirectional and Auto-Regressive Transformers) model from the `transformers` library to generate automatic text summaries. The user can either provide text directly or upload a text file to be summarized. The script allows for adjusting the minimum and maximum length of the generated summary.

The summarization functionality is powered by the `facebook/bart-large-cnn` model, one of the best models for this task.

## Features
- **Manual text input**: Allows the user to input text directly for summarization.
- **File upload**: Allows the user to upload a text file (.txt) to generate a summary.
- **Adjustable summary length**: Users can define the minimum and maximum length of the generated summary.
- **Summary history**: Displays the history of all generated summaries after each operation.

## Technologies Used
- **Transformers**: A library that simplifies the use of language models such as BART.
- **Google Colab**: Environment for running the code and uploading files.

## How to Run

1. **Install Dependencies**
   If you don't have the necessary dependencies, install them using the following command:

   ```bash
   pip install transformers google-colab
