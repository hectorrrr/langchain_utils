# Langchain Utilities

## Description

This repository is a playground to develop and document several functionalities of Langchain.
It will complement more definitive developments that may be performed in other repositories.
Currently only a unique notebook is available, with a general explanation of LangChain different component, which is just a 'slightly' more detailed and customized guide in some of the examples that LangChain's own documentation. 



## Installation

To follow this tutorial, a OpenAI API key is needed ([Get API Key](https://gptforwork.com/help/knowledge-base/create-openai-api-key)). Also we will use some LLMs from Hugging face, so a Key is also needed if that part wants to be tested ([Get Hugging Face token](https://huggingface.co/docs/api-inference/quicktour#get-your-api-token))

* Install Python (version 3.10 was used for this development).

* Clone the repository from terminal (git must be installed): 

```bash
git clone https://github.com/hectorrrr/langchain_utils.git
```



* Open a terminal in the desired directory and run (Optional):

```bash
python3.10 -m venv <your_env_name>
```

Windows:
```bash
./<your_env_name>/Scripts/activate
```

Linux:
```bash
./<your_env_name>/bin/activate
```

* Install the dependencies:
```
pip install -r requirements.txt
```

This is everything needed for the Introductory notebook ([Introduction to Langchain](./examples/langChain_intro_tutorial.ipynb))
