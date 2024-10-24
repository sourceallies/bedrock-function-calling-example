# Bedrock Function Calling Example

3 Notebooks to show different approaches to agentic function calling.

1. [`Function Calling Notebook`](./1%20-%20function_calling.ipynb) - A rudimentary version of how to do function calling with an LLM that doesn't have it integrated in by default, in this case, the AWS Bedrock platform.
2. [`Langgraph Notebook`](./2%20-%20langgraph.ipynb) - A more mature LangGraph implementation using a fake API tool, but still technically functions as a "while" loop. Similar to the ReACT decision making framework for agents.
3. [`Langgraph Rewoo Notebook`](./3%20-%20rewoo.ipynb) - Another LangGraph implementation similar to the last, except this one uses the ReWoo approach of deciding how to break down the problem, which is another popular decision making framework for agents.

## Setup

This repo uses [poetry](https://python-poetry.org/) to manage dependencies. If you don't have it installed, install it, then:

1. Run `poetry install`. This will create a virtual environment for this repo and install needed libraries.
2. Open the notebook you desire and set the execution kernel to be the poetry created virtual environment.
3. Set your AWS related variables in the first cell (Make sure you have a valid AWS token).
4. Execute all cells in order.

## Diagrams

There are diagrams in the [diagrams](./diagrams/) folder. They use draw.io formats.  You can either upload them to the website, or if you are in vscode, install the DrawIo Integration extension to be able to both view and manage the diagrams from your IDE.