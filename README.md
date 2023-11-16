# Pinecone Canopy Lab
Taking Pinecone Canopy RAG search for a spin (RAG: Retrieval-Augmented Generation).

## Setup

### Prerequisites
You need Conda installed locally (e.g. `miniconda3`). 
You also need a Pinecone API key and an OpenAI API key.

### Create the Conda Environment with Python
```
    conda create -n pinecone-canopy-lab python=3.11
    conda activate pinecone-canopy-lab
```
### Install the requirements

Canopy is available via PyPI, so you can install it with `pip` not Conda.

```
    pip install canopy-sdk
```

Alternatively, may also use the `requirements.txt` to install all the dependencies:

```
    pip install -r requirements.txt
```
