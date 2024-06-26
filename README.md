# Pegasus_Text_Summarizer
This repository contains a simple implementation of the Pegasus model for text summarization using the Hugging Face Transformers library. The Pegasus model is a state-of-the-art pre-trained model for conditional text generation, particularly well-suited for summarization tasks.

## Table of Contents
- [Installation](#installation)
- [Description](#description)
- [Acknowledgements](#acknowledgements)
- [License](#license)


## Installation

To get started, clone the repository and install the necessary packages listed in `requirements.txt`.

```bash
git clone https://github.com/pranavdhawann/Pegasus_Text_Summarizer.git
cd Pegasus_Text_Summarizer
python -m venv summary
summary/Scripts/activate
pip install -r requirements.txt
```

## Description

The provided code begins by installing essential libraries, including torch, transformers, and sentencepiece. It then imports the necessary modules, such as PegasusForConditionalGeneration and PegasusTokenizer, for text summarization. The Pegasus model and tokenizer are loaded from Hugging Face's model hub. A sample input text is defined, showcasing the application of BERT in language modeling. Parameters for summarization, such as max_length and min_length, are set to control the length of the generated summary. The code tokenizes the input text using the Pegasus tokenizer and generates a summary with specified summarization parameters. Finally, the original text and the generated summary are decoded and printed, illustrating the effective use of the Pegasus model for text summarization. Users can customize the input text and summarization parameters to tailor the summarization process to their specific requirements.

## Acknowledgements

- The Pegasus model used in this project is provided by [Hugging Face](https://huggingface.co/).
- The project is built using PyTorch and other related libraries.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
