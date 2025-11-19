# RAG-query_construction
This Python script presents a complete pipeline for constructing a Retrieval-Augmented Generation (RAG) system, encompassing the stages of indexing, retrieval, and response generation. The design is adapted from the reference implementation: https://github.com/langchain-ai/rag-from-scratch/tree/main?tab=readme-ov-file.. In contrast to the original version, which relies on the OpenAI API, this implementation substitutes the free Gemini API. Additionally, the codebase has been updated to ensure compatibility with the most recent LangChain release, incorporating changes to modules, imports, and library structure.  
This script particularly emphasizes on the **query translation techniques**, including **multi-query generation, rag-fusion, query decomposition, step-back and HyDE**. These methods are applied to enhace retrieval robustness and overall system performance.  
The relative papers:
[Decomposition]: (https://arxiv.org/pdf/2205.10625.pdf), (https://arxiv.org/abs/2212.10509.pdf)  
[Step-back]: (https://arxiv.org/pdf/2310.06117.pdf)  
[HyDE]: (https://arxiv.org/abs/2212.10496)
