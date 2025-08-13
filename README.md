# GWC2025
Girls Who Code Industry Immersion Day August 12th 2025<br>

LLM RAG Example<br>


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

- this project includes an embeddings model (converts text to numbers)
  - but you will also want to download an LLM model of your choice from https://huggingface.co/models?search=gguf
  - some common ones to look for are Google's Gemma or Meta's Llama
  - download the .gguf model file to the models folder and make sure to reference that file in the code where it loads the LLM model
 
- after setup, you can begin running the notebooks:
  - open part1_nb_add_docs_to_vectordb.ipynb
  - continue with the instructions and comments within that notebook
  - then try part2_nb_visualize_vectordb.ipynb
  - then try part3_nb_ask_llm.ipynb
  - note: once you've done part1 once, 
    - you dont need to run part1 again unless you need to add new documents
    - you can skip immediately to part3 and just ask it new questions
    - keep in sync the names of the folders between all the different notebooks
      - i.e. if you change the name of a folder in part 1, make sure that is reflected elsewhere

- have fun and keep building!
