# AI-ML-Assignment-4-Generative-LLM
 Assignment AD331: Generative AI with Pre-trained LLMs

Introduction

This program is designed to provide practical, hands-on experience with state-of-the-art Large Language Models (LLMs) using the Hugging Face Transformers library. --> (https://huggingface.co/docs/transformers/index) The notebook demonstrates how to load a pre-trained LLM from the Hugging Face Hub, run a core generative NLP task, and experiment with key decoding parameters such as temperature and max_new_tokens. A selected open-source model, LLama-variant, is used to perform all of the following tasks:

1. Text Generation – The model creates an original, creative text based on a user-defined prompt.
2. Summarization – The generated text is condensed into a concise summary.
3. Question Answering – The model answers a question derived from the generated text.
4. Parameter Experimentation – The same question is answered again using different max_new_tokens settings (e.g., 50, 150, 300) to observe how output length and style change.
5. Analysis & Visualization – The program graphically analyzes and compares the effects of varying output length on coherence, detail, and quality.

🚀 How It Works

Ensure you have a Python 3.11 environment with the following libraries:
    
    NumPy version: 2.1.3
    Pandas version: 2.2.3
    PyTorch version: 2.3.1
    Transformers version 4.46.1
    Matplotlib version: 3.10.0

Install JupyterLab/Notebook to run the provided .ipynb file, and LLM model --> TinyLlama/TinyLlama-1.1B-Chat-v1.0.

🛠 Features

- Environment Setup

```
• Install and import Hugging Face Transformers
• Load PyTorch backend
• Verify the environment and imports

``` 
- Model Loading

```
• Automatically download a pre-trained model (e.g., TinyLlama/TinyLlama-1.1B-Chat-v1.0)
• Load its corresponding tokenizer
• Initialize the text-generation pipeline

```
- Core Implementation

```
1. Text Generation: Produce an original poem, story, or narrative from a custom prompt.
2. Summarization: Reduce the generated text into 1–2 concise paragraphs.
3. Question Answering: Ask a question related to the generated text and receive a generative response.

``` 
- Parameter Experimentation – Max New Tokens

```
• 50 max_new_tokens  → short, concise answer
• 150 max_new_tokens → expanded, detailed answer
• 300 max_new_tokens → long-form, highly elaborative answer

``` 
For each run, the notebook:

```
• Captures the generated answer
• Measures text length and basic metrics (e.g., word count)
• Stores results for comparison

```

- Analysis & Charts 

```
• Differences in output size
• Trends in verbosity and repetition
• How longer generation affects coherence

```

▶️ How to Run

    Clone or download the repository.
    Open JupyterLab IDE.
    Navigate to the local repository and open 'Generative-LLM_by_DmitriySC.ipynb'.

📹 Demo

Check out the YouTube video (https://youtu.be/BrQODqAN7k8) where this model is demonstrated.
