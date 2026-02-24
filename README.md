# Writer

Multiple AI agent creation to research, write, and edit text content based on an input topic, streamlining the content creation process.

## Overview

`writer.ipynb` uses AI agents to:
- Research a given topic.
- Generate structured written content based on the research.
- Edit and refine the generated text for clarity and quality.

## Prerequisites

- Python installed on your system.
- Jupyter Notebook installed.
- Required Python packages (install via `requirements.txt`).
- An OpenAI API key set as the `OPENAI_API_KEY` environment variable.

## Usage

1. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

2. **Set API Key**:
    ```bash
    export OPENAI_API_KEY=your_api_key_here
    ```

3. **Run the Notebook**:
    - Start Jupyter Notebook:
      ```bash
      jupyter notebook
      ```
    - Open `writer.ipynb` in the Jupyter interface.
    - Provide a topic in the input cell.
    - Run the script.

## Notes

- The notebook uses the crewAI and OpenAI APIs.
- Inline comments in the notebook provide additional guidance.
- The quality of the output depends on the topic and parameters provided.
