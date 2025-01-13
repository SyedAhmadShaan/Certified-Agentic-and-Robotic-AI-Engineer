# LangChain Function/Tool Calling Calculator

## Description

This project demonstrates how to integrate LangChain's tool-calling capabilities with a conversational agent to perform basic arithmetic operations. It showcases the use of LangChain's `initialize_agent` function to create a dynamic agent capable of interpreting and executing mathematical queries.

## Features

- Uses the Gemini language model for natural language understanding.
- Defines custom Python functions as tools for arithmetic operations (addition, subtraction, multiplication, division, power, and square root).
- Utilizes LangChain's agent framework for tool selection and execution.
- Stores conversation history using `ConversationBufferMemory`.
- Provides a user-friendly interface for interacting with the agent.

## Installation

1.  **Install Dependencies:**
2.  **Set Your Gemini API Key:**

    - Obtain a Gemini API key from Google Cloud Platform.
    - Store the API key in Google Colab userdata using:
      python from google.colab import userdata userdata.set('GOOGLE_API_KEY', 'YOUR_API_KEY')

    ## Usage

3.  **Run the Notebook:** Execute all cells in the Jupyter Notebook to initialize the agent and its dependencies.
4.  **Start a Conversation:** Use the `agent.run()` method to interact with the agent:
    python query = "What is 3 \* 12?" response = agent.run(query) print("Agent's Response:", response)

## Examples

- **"What is 3 \* 12?"** - The agent will respond with "36".
- **"Calculate the square root of 25."** - The agent will respond with "5".
- **"Add 10 and 5."** - The agent will respond with "15".

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License.
