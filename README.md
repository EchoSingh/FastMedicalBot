# 🩺 FAST MEDICAL Chatbot

![Medical Bot](https://cdn.dribbble.com/users/29678/screenshots/2407580/media/34ee4b818fd4ddb3a616c91ccf4d9cfc.png)

![Result](https://github.com/aditya26062003/FastMedicalBot/blob/main/result1.png)
## Get Answers in Seconds

This repository contains a medical chatbot powered by the Medical-Llama3-8B model. The chatbot is designed to assist users with medical queries using a conversational retrieval chain.

## Features

- Utilizes the `Medical-Llama3-8B` model for medical information.
- Incorporates document embeddings and a vector store for improved information retrieval.
- Provides a user-friendly interface with Gradio.
- Customizable model parameters through the Gradio interface.

## Setup

### Prerequisites

- Python 3.7 or higher
- CUDA-compatible GPU (for running the model efficiently)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/medical-chatbot.git
    cd medical-chatbot
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Install the `bitsandbytes`, `transformers`, and `accelerate` packages:

    ```bash
    pip install --upgrade bitsandbytes transformers accelerate -i https://pypi.org/simple/
    ```

### Using the Model

Download the `Medical-Llama3-8B` model from this [link](https://huggingface.co/ruslanmv/Medical-Llama3-8B).

## Usage

1. Run the Jupyter cell code.

2. Open the provided link to access the Gradio interface.

### Example Usage

Here's an example of how to use the chatbot:

- Type your question in the provided textbox.
- Adjust the parameters like `Max New Tokens`, `Temperature`, and `Context Length` as needed.
- Get the response from the chatbot displayed in a scrollable box.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The `Medical-Llama3-8B` model by [ruslanmv](https://huggingface.co/ruslanmv)
- [Gradio](https://gradio.app/) for providing a user-friendly interface for machine learning models
