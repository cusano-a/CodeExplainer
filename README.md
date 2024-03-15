# Code Understanding with Local LLMs

This notebook provides insights into building a Code Understanding App using Local LLMs and a RAG architecture.

**Use Cases**

In the realm of software development, grappling with ill documented or poorly written code is a common challenge that consumes valuable time and resources. 

Despite source code analysis being one of the most popular LLM applications, traditional web-based interfaces come with their own set of limitations.
One primary constraint is the restricted context provided by these interfaces, making it challenging to grasp the full scope and intricacies of the code under examination. Moreover, concerns regarding data privacy and security loom large, as sensitive codebases may contain proprietary or confidential information that cannot be safely processed on remote servers.

By leveraging the power of Retrieval-Augmented Generation (RAG) combined with a model running locally, these concerns can be at least alleviated.
Indeed, this approach could help developers navigating through complex codebases with greater efficiency and confidence, while preserving data privacy and security. 


**Tech Stack**

- LangChain (Application Framework)
- HuggingFace SentenceTransformers (Text Embedding)
- FAISS (Vector Store)
- Ollama (Local LLMs Platform)
- Gemma:7b (LLM)

**Sources** 

Most of the content of this notebook follow along the documentation and example pages of [LangChain documentation](https://python.langchain.com/docs/get_started/introduction). We tried gathering and integrating further details for a novice of the LLM landscape. Please refer to the linked original sources whenever possible.