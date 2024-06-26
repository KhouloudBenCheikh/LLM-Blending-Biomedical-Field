# LLM Blending in the Biomedical Field 💉

This repository contains code a Medical Chatbot trained with various Models tailored for the Biomedical domain. 

The goal of this project is to develop a robust **Large Language Model (LLM)** using the Blending Model Method, aiming to improve question-answering and Medical dialogue tasks in the Healthcare domain.

## The Base Model: BioMistral-7B

- **Description**: BioMistral is an open-source Large Language Model (LLM) designed specifically for the Biomedical domain. It is built on top of the Mistral foundation model and further pre-trained on PubMed Central data.
- **Evaluation**: A comprehensive evaluation of BioMistral was conducted on a benchmark comprising 10 established Medical question-answering (QA) tasks in English.
- **Approaches**: Lightweight models obtained through quantization and Model merging approaches were explored.
- **Official Link**: https://huggingface.co/BioMistral/BioMistral-7B

## 2nd Model: Meditron-7B

- **Description**: Meditron is a suite of open-source Medical Large Language Models (LLMs). 
  
  Meditron-7B is a <u>7 billion Parameters Model</u>
 adapted to the Medical domain from <u>Llama-2-7B</u>. It was further pre-trained on a comprehensively curated Medical corpus, including selected PubMed articles, abstracts, Medical guidelines, and general domain data from <u>RedPajama-v1</u>.
- **Performance**: Meditron-7B, finetuned on relevant training data, outperforms <u>Llama-2-7B</u> and <u>PMC-Llama</u> on multiple Medical reasoning tasks.
- **Official Link**: https://huggingface.co/epfl-llm/meditron-7b
  
## 3th Model: Medalpaca-7B

- **Description**: Medalpaca-7B is a Large Language Model specifically fine-tuned for Medical domain tasks. It is based on <u>LLaMA (Large Language Model Meta AI)</u> and contains <u>7 billion parameters</u>.
- **Objective**: The primary goal of this model is to improve question-answering and Medical dialogue tasks.
- **Official Link**: https://huggingface.co/medalpaca/medalpaca-7b

For detailed information about each model and their respective architectures, please refer to the model documentation provided.

## Usage

To generate text using these models, follow the instructions provided in the code files.