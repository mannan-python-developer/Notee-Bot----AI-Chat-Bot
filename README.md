# Notee Bot

Notee Bot is an AI-powered tool designed to assist users in searching through and generating content based on text data. It utilizes natural language processing (NLP) techniques and the power of deep learning to provide relevant information or generate responses.

## Features

1. **Text Data Processing:** Notee Bot can read and process text data from multiple files stored in a specified directory, enabling users to organize and search through their notes efficiently.
2. **Search Functionality:** Users can search for specific queries within their notes, and Notee Bot provides relevant matches found within the stored text data.
3. **GPT-2 Integration:** In cases where a query is not found within the notes, Notee Bot leverages the GPT-2 language model to generate responses based on the user's input.

## How to Use

1. **Input Query:** Users can enter their queries via the provided text box interface.
2. **Search in Notes:** Notee Bot first searches for the query within the pre-existing notes. If a match is found, it displays the relevant content.
3. **GPT-2 Generation:** If the query is not found within the notes, Notee Bot uses the GPT-2 model to generate a response based on the query.

## Usage

To use Notee Bot:

1. Clone or download the repository.
2. Install the required dependencies specified in the `requirements.txt` file.
3. Run the `Notee_Bot.py` script.
4. Interact with the bot via the provided Gradio interface.

## Dependencies

- torch
- pandas
- transformers
- gradio

## Acknowledgments

- This project utilizes the Hugging Face `transformers` library for accessing the GPT-2 model.
- Gradio is used to create the user-friendly interface for interacting with Notee Bot.

## License

This project is licensed under the [MIT License](LICENSE).
