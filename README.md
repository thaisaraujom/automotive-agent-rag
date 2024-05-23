# Automotive Agent RAG

## Overview

Welcome to the Automotive Agent RAG repository. This project leverages Retrieval-Augmented Generation (RAG) to facilitate queries related to automotive manuals. By integrating intelligent agents, the system provides accurate and context-specific information about various automotive models.

## Features

- **Retrieval-Augmented Generation (RAG):** uses RAG techniques to enhance the accuracy of information retrieval.
- **Automotive-Specific Queries:** tailored for handling queries related to different car makes, models, and years.
- **Intelligent Agents:** employs advanced AI agents to understand and process user requests effectively.
- **Milvus Integration:** utilizes Milvus for efficient vector similarity search and retrieval.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.10 or later
- Jupyter Notebook
- Docker (if using Milvus with Docker)
- An OpenAI API key
- Required Python libraries (see `requirements.txt`)

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/thaisaraujom/automotive-agent-rag.git
    ```
2. Navigate to the project directory:
    ```sh
    cd automotive-agent-rag
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Setting Up Milvus

You have the option to set up Milvus either locally or using Docker. For detailed instructions on both methods, please refer to the [Milvus Documentation](https://milvus.io/docs/).

### Setting Up OpenAI API Key

If you do not have an OpenAI API key, you can sign up for an account on the [OpenAI website](https://www.openai.com/) and generate an API key.

### Usage

To run the project, follow these steps:

2. Open the `agent_rag_manual.ipynb` file in you Jupyter Notebook environment.
3. Follow the instructions within the notebook to execute the cells and interact with the system.

## Project Structure

- `agent_rag_manual.ipynb`: main Jupyter Notebook containing the implementation.
- `requirements.txt`: list of dependencies required to run the project.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
