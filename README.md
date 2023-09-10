# 📦 Streamlit-Example-DocumentDL 
```
⬆️ (Replace above with your app's name)
```

Description of the app ...

## DocumentDL

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://app-starter-kit.streamlit.app/)

## GitHub Codespaces

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/streamlit/app-starter-kit?quickstart=1)

## Transformers

There are three types of architectures in Transformers

Encoder : suited for task requiring an understanding of the full sentence, such as sentence classification, NER,extractive question Answering. Example: BERT

Decoder : suited for task involving text generation. Example: GPT-3

Encoder-Decoder : suited for tasks around generating new sentences depending on a given input such as summarization, Translation or generating question Answering. Example: t5, multilingual-mt5

## Implementation

Create a virtual environment

Install necessary libraries

pip install streamlit transformers torch pdf2image

Run the application

 streamlit run <fileName.py>
Upload a pdf document in streamlit window. Automatically it extracts text and display the extracted text

Now, user can enter any question related the extracted text in the input field .Press Enter to get the answer

User can ask questions more number of times to the bot in the input field.


