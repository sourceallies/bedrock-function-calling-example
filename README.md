# Bedrock Function Calling Example

Small repo to show a rudimentary version of how to do function calling with an LLM that doesn't have it integrated in by default, in this case, the AWS Bedrock platform.

## Setup

This repo uses [poetry](https://python-poetry.org/) to manage dependencies. If you don't have it installed, install it, then:

1. Run `poetry install`. This will create a virtual environment for this repo and install needed libraries.
2. Open the [notebook](function_calling.ipynb) and set the execution kernel to be the poetry created virtual environment.
3. Set your AWS related variables in the first cell (Make sure you have a valid AWS token).
4. Execute all cells in order.

## Diagrams

There are diagrams in the [diagrams](./diagrams/) folder. They use draw.io formats.  You can either upload them to the website, or if you are in vscode, install the Drawio Integration extension to be able to both view and manage the diagrams from your IDE.