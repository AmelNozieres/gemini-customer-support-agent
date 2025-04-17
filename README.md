#  Gemini-Powered Customer Support Agent (GenAI Capstone)

This project is a working MVP of a GenAI customer support agent — built using Gemini, function calling, document retrieval, and structured output.

It was created as part of the **Kaggle x Google GenAI Capstone (2025)**.

---

##  What It Can Do

The agent:
- Classifies incoming support messages using Gemini (zero-shot)
- Detects urgency (priority) with hybrid logic
- Retrieves relevant KB documents via RAG (embeddings + cosine similarity)
- Calls live functions to access invoice/order/payment data
- Controls tone based on the message category
- Simulates short-term memory using previous messages
- Evaluates its own responses (scoring + feedback)
- Logs all interactions to a CSV (MLOps-style)

---

##  Notebook

> ✅ View the final notebook on Kaggle:  
> https://www.kaggle.com/code/amelnozieres/notebooka52303bfad

You can run it directly in Kaggle — no setup required.

---

## 📚 Articles & Demos

### Final Version
- 📖 [How I Built a Smarter GenAI Customer Agent (Substack)](https://decryptai.substack.com/p/how-i-built-a-smarter-genai-customer)
- 🎥 [Demo Video](https://youtu.be/LHebeTt_JtA)

### Original MVP (V1)
- 📖 [Building a Customer Support Agent](https://decryptai.substack.com/p/building-a-customer-support-agent)
- 🎥 [Walkthrough Video](https://youtu.be/O9rHu1t8fTM)

---

## 🚀 Try It Locally

> 💡 Note: This notebook is designed to run in Kaggle.  
> If you want to use Gemini API locally, make sure to:
- Install `google-generativeai`
- Set your `GOOGLE_API_KEY` as an environment variable
- Have Python 3.10+ and access to a Gemini-compatible model

---

## 👩‍💻 Author

**Amal Nozieres**  
→ [Substack](https://decryptai.substack.com)  
→ [LinkedIn](https://www.linkedin.com/in/amalnozieres)

---

## 🪪 License

MIT License (feel free to fork, remix, and adapt)
