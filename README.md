# GWC2025
LLM RAG Example


- Step 0. install dependencies, (execute only once)
  - note: use python 3.10 for maximum compatibility

- install Anaconda https://www.anaconda.com/download/success and VS Code https://code.visualstudio.com/
  - then create a new conda environment with python 3.10 in the terminal or anaconda command prompt
  - conda create -n llm python=3.10
  - conda activate llm

- then install the dependencies below
  - pip install langchain chromadb sentence-transformers pymupdf
  - pip install langchain-community
  - pip install llama-cpp-python
  - pip install umap-learn pandas scikit-learn matplotlib plotly nbformat

- this includes an embeddings model (converts text to numbers)
  - you will want to download an LLM model from https://huggingface.co/models?search=gguf
  - some common ones to look for are Google's Gemma or Meta's Llama
  - download the .gguf model file to the models folder and make sure to reference that file in the code where it loads the LLM model
