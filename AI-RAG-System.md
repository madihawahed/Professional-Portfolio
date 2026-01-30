# **Artifact Title**- Enterprise Knowledge Retrieval: Implementing a RAG System for Data-Driven AI

## **Introduction**
This artifact is a comprehensive case study (Assignment 3.3) exploring the implementation of a Retrieval-Augmented Generation (RAG) system for a large-scale food and beverage retailer. The project addresses the "Information Overload" challenge by transforming static legacy PDFs and manuals into a dynamic, real-time AI "Expert Assistant" for store employees and compliance officers.
<img width="1024" height="1024" alt="ooo" src="https://github.com/user-attachments/assets/614edfab-6d42-44df-8ed3-a6f95b0353f9" />


## **Artifact Description**
*Objective*: To reduce "hallucinations" in AI outputs by providing the model with access to a specific, vetted knowledge base (PDFs/Docs) before generating a response.

*Process*: I individually developed a workflow that involves document ingestion, text chunking, embedding generation, and vector database storage. The final step was creating a retrieval loop that pulls relevant context for every user query.

*Tools and Technologies Used*: Vector Databases (e.g., Pinecone or Weaviate), LangChain framework, Python, and OpenAI/Anthropic API for the generation layer.

## **Artifact-Specific Value Proposition**

*Unique Value*: This artifact showcases my ability to handle the "Last Mile" of AI implementation—ensuring that the AI actually knows the specific facts relevant to a business rather than just general internet knowledge.

*Relevance*: It aligns with my value proposition of being an AI leader who prioritizes accuracy and data security over "black box" solutions.

## **Customization for Audience**

*Adaptations Made*: I included a specific visualization of the "Retrieval vs. Generation" flow to explain the technical process to non-technical project stakeholders.

*Relevance*: This customization helps managers understand that RAG is a safer, more cost-effective alternative to full model fine-tuning.

## **Reflection**

*Significance*: I chose this because RAG is currently the industry standard for enterprise AI. Mastering this demonstrates that I am current with modern AI architecture.

*Lessons Learned*: I learned that "Garbage In, Garbage Out" applies heavily to embeddings; the way data is cleaned and chunked is more important than the actual LLM used for the final response.

<img width="842" height="473" alt="1747733686565" src="https://github.com/user-attachments/assets/8c4a93ef-d04a-4a3c-aca7-01263e4cec48" />


## **Feedback and Revisions**

*Feedback*: Initial feedback suggested that the system was too slow during the retrieval phase.

*Revisions*: I optimized the chunking strategy and implemented metadata filtering, which significantly decreased latency and improved result relevance.

## **References**

"Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks" (Lewis et al.).

LangChain Documentation on Vector Stores.

Link to Artifact:
https://madihawahed.github.io/rag-case-study/
