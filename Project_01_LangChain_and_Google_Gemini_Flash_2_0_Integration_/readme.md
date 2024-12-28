# LangChain with Google Gemini Flash 2.0

This project demonstrates a simple question-answering system using LangChain and the Google Gemini Flash 2.0 AI model.

## Google Colab Link:

https://colab.research.google.com/drive/1L7fPeJg7AtibskKqAnw2CDT7veYJYfE_?usp=sharing

## Project Overview

The project showcases how to:

1. Install necessary packages (`langchain-google-genai`).
2. Set up your Google API key.
3. Initialize the Gemini 2.0 Flash Exp model with LangChain.
4. Create a prompt template for structuring questions.
5. Build an LLMChain for easy interaction with the AI model.
6. Ask questions and display the answers.

## Requirements

- Python 3.7 or higher
- `langchain-google-genai` package
- A Google Cloud Project with the Gemini API enabled
- A Google API Key stored securely in your Colab environment

## Setup

1. **Install `langchain-google-genai`:**
2. **Store your Google API Key:**

   - Go to your Google Cloud Console and create an API key.
   - In your Google Colab notebook, store the API key securely using `google.colab.userdata`:

   ## Running the Code

3. Open the Jupyter notebook associated with this project.
4. Run all the cells in the notebook.
5. Observe the questions and answers printed in the output.

## Code Explanation

The code is structured in steps:

- **Step 1 & 2:** Installs the necessary package and sets up the API key.
- **Step 3:** Initializes the Google Gemini Flash 2.0 model.
- **Step 4:** Defines a prompt template for questions.
- **Step 5:** Creates an LLMChain for interacting with the model.
- **Step 6:** Defines a list of questions, sends them to the model, and prints the responses.

## Customization

- **Change the Questions:** Modify the `questions` list in the code to ask your own questions.
- **Adjust Model Parameters:** Explore different values for `temperature` in the `ChatGoogleGenerativeAI` initialization to control the randomness of the AI's responses.

## Disclaimer

This is a basic example for demonstration purposes. For more advanced use cases, explore LangChain's documentation and the capabilities of the Google Gemini API.
