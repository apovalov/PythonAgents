# PythonAgentAI

PythonAgentAI is an artificial intelligence agent based on LLamaIndex designed to process queries related to demographic data and country information. 
It utilizes various tools and data to handle queries and provide accurate information.

## Installation

To use PythonAgentAI, first clone the repository and install dependencies:

```bash
pip install -r requirements.txt
```

## Setup
Create and activate a Python virtual environment.
Download the necessary data as instructed in the video.

## Usage
To get started with PythonAgentAI, follow these steps:

Run `main.py` and follow the on-screen instructions to input queries.
The agent can process queries about population and demographic data, as well as provide information from PDF files.

## Features
Population Query Handling: Uses PandasQueryEngine for processing queries related to demographic data.
Working with Unstructured Data: Uses VectorStoreIndex and PDFReader for processing information from PDF files.
Note Saving: Ability to save notes using the note_saver tool.

## Example Queries
What is the population of Canada? - The agent uses `PandasQueryEngine` to process this query.
Provide information about Canada from a PDF - The agent uses VectorStoreIndex to retrieve information from a PDF file.

