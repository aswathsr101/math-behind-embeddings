# Math Behind Embeddings

This Jupyter notebook explores the mathematical concepts behind vector spaces and embeddings in Natural Language Processing (NLP) and Large Language Models (LLMs). It provides practical examples using Amazon Bedrock and Amazon Titan Text Embeddings V2.

## Table of Contents

1. [LLM Embeddings as an Application of Vector Spaces](#1)
2. [Distance and Similarity in Vector Space](#2)
3. [Analogy Reasoning](#3)

## <a name="1">1. LLM Embeddings as an Application of Vector Spaces</a>

This section introduces the concept of vector spaces and how they are applied in NLP through embeddings. It covers:
- Definition and properties of vector spaces
- Practical example using Amazon Titan Text Embeddings V2

## <a name="2">2. Distance and Similarity in Vector Space</a>

This section explains how to measure the similarity between vectors in the embedding space using:
- Cosine Similarity
- Euclidean Distance

It includes functions to compute these metrics and examples comparing words and sentences.

## <a name="3">3. Analogy Reasoning</a>

This section demonstrates analogy reasoning using vector operations on embeddings. It includes:
- Function to perform analogy reasoning
- Examples with word analogies and country-capital relationships

## Requirements

- Python 3.11.10
- Jupyter Notebook
- Required libraries: `pandas`, `matplotlib`, `scikit-learn`, `boto3`, `numpy`

## Installation

To install the required libraries, run the following commands:

```python
!pip install -q --upgrade pip
!pip install -q --upgrade scikit-learn pandas matplotlib boto3 numpy
```

## Usage

1. Open the notebook in Jupyter.
2. Run the cells sequentially to explore the concepts and examples.
3. Modify the examples or add new ones to further explore embeddings and vector spaces.

## License

This project is licensed under the MIT License.
