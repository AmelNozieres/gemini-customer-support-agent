# gemini-customer-support-agent
Kaggle gemini-customer-support-agent


#### **Project Title**  
**SmartMail: A Gemini-Powered Customer Support Email Agent**

#### **Problem**  
Customer support teams receive large volumes of repetitive, unstructured emails that require manual classification and personalized replies. This is time-consuming, costly, and inconsistent across agents.

#### **Solution**  
This project demonstrates a Generative AI-powered **Customer Support Email Agent** built entirely using Gemini models. The system:
- Classifies incoming emails into support categories
- Retrieves the most relevant knowledge base documents using embeddings
- Generates grounded and helpful replies using Gemini 2.0 Flash

#### **User Flow**
1. Input: Email (subject + body)
2. Step 1: Gemini zero-shot classification into 5 categories
3. Step 2: Document retrieval using cosine similarity over Gemini-generated embeddings
4. Step 3: Reply generation using Gemini 2.0 Flash, grounded in retrieved context

---

#### **GenAI Capabilities Demonstrated**

| Capability                       | Description                                                              |
|----------------------------------|--------------------------------------------------------------------------|
| **Document Understanding**       | Extracts user intent from unstructured customer emails                   |
| **Embeddings**                   | Generates vector representations of support content using Gemini         |
| **Retrieval-Augmented Generation (RAG)** | Retrieves relevant context before generating responses             |
| **Grounding**                    | LLM responses are directly grounded in retrieved documents               |
| **Agents**                       | Multi-step workflow: classify → retrieve → generate reply                |

---

#### **Why This Matters**
This project simulates a real-world use case of automating customer support with GenAI — reducing human workload while maintaining personalization and accuracy.

---

✅ Built using:  
- `google-generativeai`  
- `text-embedding-004`  
- `gemini-2.0-flash`  
- Python, Pandas, Sklearn, TQDM  
- Cosine similarity for retrieval (no FAISS)
