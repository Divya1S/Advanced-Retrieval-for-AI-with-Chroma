```html
<!DOCTYPE html>
<html>
<head>
    <title>Information Retrieval and RAG Enhancement Techniques</title>
</head>
<body>
    <h1>Information Retrieval and RAG Enhancement Techniques</h1>
    <p>This repository contains Jupyter notebooks (<code>L1.ipynb</code> to <code>L5.ipynb</code>) demonstrating advanced techniques to improve the relevancy of results in Information Retrieval (IR) and Retrieval Augmented Generation (RAG). These techniques address the common issue where queries return semantically similar but irrelevant results, or include distracting material that can mislead a Large Language Model (LLM).</p>

    <h2>Overview</h2>
    <p>Effective IR and RAG depend on retrieving information from a database that is both relevant to the query and useful for its intended application. The notebooks in this repository explore methods to enhance retrieval relevancy, focusing on the following techniques:</p>
    <ol>
        <li><b>Query Expansion</b>: Enhances user queries by incorporating related concepts and keywords. Using an LLM, this traditional technique becomes more effective. Another approach involves the LLM suggesting a possible answer, which is then included in the query to refine results.</li>
        <li><b>Cross-encoder Reranking</b>: Improves retrieval by reranking results to prioritize those most relevant to the query.</li>
        <li><b>Training and Utilizing Embedding Adapters</b>: Adds an adapter layer to reshape embeddings, emphasizing elements relevant to the specific application.</li>
    </ol>

    <h2>Notebooks</h2>
    <ul>
        <li><b>L1.ipynb</b>: Introduction to IR and RAG, with an overview of challenges in retrieving relevant results.</li>
        <li><b>L2.ipynb</b>: Implementation of Query Expansion using an LLM to include related concepts and keywords.</li>
        <li><b>L3.ipynb</b>: Advanced Query Expansion with LLM-suggested answers integrated into the query.</li>
        <li><b>L4.ipynb</b>: Cross-encoder Reranking to prioritize the most relevant retrieval results.</li>
        <li><b>L5.ipynb</b>: Training and applying Embedding Adapters to enhance retrieval relevancy.</li>
    </ul>

    <h2>Getting Started</h2>
    <ol>
        <li><b>Prerequisites</b>:
            <ul>
                <li>Python 3.8+</li>
                <li>Jupyter Notebook or JupyterLab</li>
                <li>Libraries: (Specify required libraries, e.g., <code>transformers</code>, <code>numpy</code>, <code>torch</code>, etc., as used in the notebooks)</li>
            </ul>
        </li>
        <li><b>Installation</b>:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li><b>Running the Notebooks</b>:
            <ul>
                <li>Open the desired notebook (<code>L1.ipynb</code> to <code>L5.ipynb</code>) in Jupyter.</li>
                <li>Follow the instructions within each notebook to explore the respective technique.</li>
            </ul>
        </li>
    </ol>
</body>
</html>
```
