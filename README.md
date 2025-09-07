</head>
<body>
    <h1>Information Retrieval and RAG Enhancement Techniques</h1>
    <p>This repository contains Jupyter notebooks (<code>L1.ipynb</code> to <code>L5.ipynb</code>) demonstrating advanced techniques to improve the relevancy of results in Information Retrieval (IR) and Retrieval Augmented Generation (RAG). These techniques address the common issue where queries return semantically similar but irrelevant results, or include distracting material that can mislead a Large Language Model (LLM).</p>

    <h2>Overview</h2>
    <p>Effective IR and RAG depend on retrieving information from a database that is both relevant to the query and useful for its intended application. The notebooks in this repository explore methods to enhance retrieval relevancy, focusing on the following techniques:</p>
    <ol>
        <li><strong>Query Expansion</strong>: Enhances user queries by incorporating related concepts and keywords. Using an LLM, this traditional technique becomes more effective. Another approach involves the LLM suggesting a possible answer, which is then included in the query to refine results.</li>
        <li><strong>Cross-encoder Reranking</strong>: Improves retrieval by reranking results to prioritize those most relevant to the query.</li>
        <li><strong>Training and Utilizing Embedding Adapters</strong>: Adds an adapter layer to reshape embeddings, emphasizing elements relevant to the specific application.</li>
    </ol>

    <h2>Notebooks</h2>
    <ul>
        <li><strong>L1.ipynb</strong>: Introduction to IR and RAG, with an overview of challenges in retrieving relevant results.</li>
        <li><strong>L2.ipynb</strong>: Implementation of Query Expansion using an LLM to include related concepts and keywords.</li>
        <li><strong>L3.ipynb</strong>: Advanced Query Expansion with LLM-suggested answers integrated into the query.</li>
        <li><strong>L4.ipynb</strong>: Cross-encoder Reranking to prioritize the most relevant retrieval results.</li>
        <li><strong>L5.ipynb</strong>: Training and applying Embedding Adapters to enhance retrieval relevancy.</li>
    </ul>

    <h2>Getting Started</h2>
    <ol>
        <li><strong>Prerequisites</strong>:
            <ul>
                <li>Python 3.8+</li>
                <li>Jupyter Notebook or JupyterLab</li>
                <li>Libraries: (Specify required libraries, e.g., <code>transformers</code>, <code>numpy</code>, <code>torch</code>, etc., as used in the notebooks)</li>
            </ul>
        </li>
        <li><strong>Installation</strong>:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li><strong>Running the Notebooks</strong>:
            <ul>
                <li>Open the desired notebook (<code>L1.ipynb</code> to <code>L5.ipynb</code>) in Jupyter.</li>
                <li>Follow the instructions within each notebook to explore the respective technique.</li>
            </ul>
        </li>
    </ol>

    <h2>Usage</h2>
    <p>Each notebook is self-contained and includes code, explanations, and examples. Start with <code>L1.ipynb</code> for a foundational understanding, then proceed to the other notebooks to dive into specific techniques.</p>

    <h2>Contributing</h2>
    <p>Contributions are welcome! Please submit a pull request or open an issue to suggest improvements or report bugs.</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
