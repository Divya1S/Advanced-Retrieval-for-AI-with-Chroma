# Information Retrieval and RAG Enhancement Techniques

This repository contains Jupyter notebooks (`L1.ipynb` to `L5.ipynb`) demonstrating advanced techniques to improve the relevancy of results in Information Retrieval (IR) and Retrieval Augmented Generation (RAG). These techniques address the common issue where queries return semantically similar but irrelevant results, or include distracting material that can mislead a Large Language Model (LLM).

---

## Overview

Effective IR and RAG depend on retrieving information from a database that is both relevant to the query and useful for its intended application. The notebooks in this repository explore methods to enhance retrieval relevancy, focusing on the following techniques:

1. **Query Expansion**  
   Enhances user queries by incorporating related concepts and keywords. Using an LLM, this traditional technique becomes more effective. Another approach involves the LLM suggesting a possible answer, which is then included in the query to refine results.

2. **Cross-encoder Reranking**  
   Improves retrieval by reranking results to prioritize those most relevant to the query.

3. **Training and Utilizing Embedding Adapters**  
   Adds an adapter layer to reshape embeddings, emphasizing elements relevant to the specific application.

---

## Notebooks

- **L1.ipynb**: Introduction to IR and RAG, with an overview of challenges in retrieving relevant results.  
- **L2.ipynb**: Implementation of Query Expansion using an LLM to include related concepts and keywords.  
- **L3.ipynb**: Advanced Query Expansion with LLM-suggested answers integrated into the query.  
- **L4.ipynb**: Cross-encoder Reranking to prioritize the most relevant retrieval results.  
- **L5.ipynb**: Training and applying Embedding Adapters to enhance retrieval relevancy.  

---

## Getting Started

### Prerequisites
- Python 3.8+  
- Jupyter Notebook or JupyterLab  
- Libraries: `transformers`, `numpy`, `torch`, and other dependencies as specified in the notebooks  

### Installation
```bash
pip install -r requirements.txt

