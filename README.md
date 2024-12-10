# QA with RAG Model on Climate Fever  

This project demonstrates how to use a Retrieval-Augmented Generation (RAG) model for question answering on the Climate Fever dataset. Built with the Haystack framework, it integrates retrieval and generation to provide accurate answers to queries.  

---

## Features  

- Use Haystack to build and configure a RAG model.  
- Query the model for detailed answers from the Climate Fever dataset.  
- Fine-tune and evaluate model performance.  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/qa-rag-climate-fever.git  
   cd qa-rag-climate-fever  
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt  
   ```

Repository Name
qa-rag-climate-fever

Description
Experimenting with a QA RAG Model on Climate Fever Dataset

This repository demonstrates how to use the Haystack framework to build and experiment with a Retrieval-Augmented Generation (RAG) model for question-answering (QA) tasks. The notebook focuses on the Climate Fever dataset, guiding users through integrating the components of a RAG model and querying it for answers.

README.md
markdown
Copy code
# QA with RAG Model on Climate Fever  

This project uses the **Haystack** framework to build a Retrieval-Augmented Generation (RAG) model for question answering (QA) on the **Climate Fever** dataset. The RAG model combines retrieval and generation capabilities, allowing it to provide accurate, contextually relevant answers to queries.  

---

## Features  

- Integrate and fine-tune components of a RAG model.  
- Use the Climate Fever dataset for context-aware question answering.  
- Experiment with prompting queries and retrieving detailed answers.  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/qa-rag-climate-fever.git  
   cd qa-rag-climate-fever  

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
1. Open the notebook:
``` bash
jupyter notebook qa_rag_climate_fever.ipynb
```
or use google colab 

2. Ensure the runtime is set to GPU or TPU for faster training and inference.

3. Follow the steps in the notebook to:
  - Load the Climate Fever dataset.
  - Configure the RAG model using Haystack.
  - Query the model for detailed answers to climate-related questions.

## Dependencies
haystack (farm-haystack[colab] for google colab)

datasets

jupyter

Install them using the requirements.txt file.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The Climate Fever dataset is provided for research on fact verification and QA.
- This project uses the Haystack framework for building RAG models.

