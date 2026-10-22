# RAG Journal Club

Materials for our department journal club session on **retrieval-augmented generation (RAG)**.
Presenter: Hezi Liu

## Reading List

The five papers below were selected as the most relevant results from an arXiv catalog search on retrieval-augmented generation. All titles, authors, and arXiv IDs are recorded exactly as returned by the catalog.

### 1. Active Retrieval Augmented Generation
- **Authors:** Zhengbao Jiang, Frank F. Xu, Luyu Gao, Zhiqing Sun, Qian Liu, Jane Dwivedi-Yu, Yiming Yang, Jamie Callan, Graham Neubig
- **arXiv ID:** 2305.06983
- **Takeaway:** FLARE actively decides when and what to retrieve across the course of generation, using low-confidence predictions of the upcoming sentence as retrieval queries — beating once-only retrieve-then-generate baselines on long-form knowledge-intensive tasks.

### 2. Corrective Retrieval Augmented Generation
- **Authors:** Shi-Qi Yan, Jia-Chen Gu, Yun Zhu, Zhen-Hua Ling
- **arXiv ID:** 2401.15884
- **Takeaway:** CRAG adds a lightweight retrieval evaluator that scores retrieval quality and triggers corrective actions (including large-scale web search and decompose-then-recompose filtering), making RAG robust even when retrieval goes wrong.

### 3. Dynamic Retrieval-Augmented Generation
- **Authors:** Anton Shapkin, Denis Litvinov, Yaroslav Zharov, Egor Bogomolov, Timur Galimzyanov, Timofey Bryksin
- **arXiv ID:** 2312.08976
- **Takeaway:** Instead of appending raw retrieved text to the prompt, DRAG injects compressed embeddings of retrieved entities, lifting context-window limits and scaling the number of usable retrieval entities, demonstrated on project-level code generation.

### 4. A Survey on Retrieval-Augmented Text Generation
- **Authors:** Huayang Li, Yixuan Su, Deng Cai, Yan Wang, Lemao Liu
- **arXiv ID:** 2202.01110
- **Takeaway:** A systematic survey organizing retrieval-augmented text generation along its core dimensions (retriever, generator, and their augmentation paradigm), a good map of the field before diving into the method papers.

### 5. R^2AG: Incorporating Retrieval Information into Retrieval Augmented Generation
- **Authors:** Fuda Ye, Shuangyin Li, Yongqi Zhang, Lei Chen
- **arXiv ID:** 2406.13249
- **Takeaway:** R^2AG uses retrieval information itself as features to adapt the language model, narrowing the semantic gap between retrievers and LLMs that arises from their differing training objectives and architectures.

## Background Reading

- **Attention Is All You Need**
  - **Authors:** Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin
  - **arXiv ID:** 1706.03762
  - The seminal Transformer paper — the architecture underlying the language models that RAG augments. (ID confirmed against the arXiv catalog.)
