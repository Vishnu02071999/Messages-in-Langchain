# Messages-in-Langchain


This project demonstrates how to use **SystemMessage** and **HumanMessage** in LangChain to control the behavior of a Large Language Model (LLM).

The example configures the model to act as a Python programming expert and respond only with code. A user request is then sent asking for a function that adds two numbers.

## Features

- Uses OpenAI models through LangChain
- Loads API keys securely using `.env`
- Demonstrates role-based prompting with `SystemMessage`
- Sends user instructions through `HumanMessage`
- Generates code-only responses

## Learning Outcomes

After completing this project, you will understand:

- What SystemMessage is and why it is important
- How HumanMessage represents user input
- How message-based prompting works in LangChain
- How to control LLM behavior through system instructions
- How to interact with OpenAI models using LangChain

## Technologies Used

- Python
- LangChain
- OpenAI
- python-dotenv

