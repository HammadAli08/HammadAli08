<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:2563EB,100:3D00FF&height=230&section=header&text=Hammad%20Ali%20Tahir&fontSize=48&fontColor=FFFFFF&fontAlignY=38&desc=AI%20Engineering%20%7C%20Generative%20AI%20%7C%20Agentic%20Systems&descSize=17&descAlignY=59" alt="Hammad Ali Tahir — AI Engineering, Generative AI, Agentic Systems" width="100%" />

  <h1>AI Engineer · RAG Developer · Agentic Workflow Builder</h1>
  <h3>Connecting language models, retrieval systems, and real-world applications.</h3>
  <p><strong>AI Trainee Engineer Intern @ Analytiverse</strong><br />BS Computer Science Graduate · University of Education, Lahore · Class of 2026</p>
</div>

<p align="center">
  <a href="https://www.linkedin.com/in/hammad-ali08/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://fedora-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Fedora_Portfolio-3C6EB4?style=for-the-badge&logo=fedora&logoColor=white" alt="Fedora Portfolio" /></a>
  <a href="mailto:hammadalitahir8@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/HammadAli08?tab=repositories"><img src="https://img.shields.io/badge/Explore_My_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore my repositories" /></a>
</p>

<p align="center">
  <a href="#about-me">About</a> ·
  <a href="#engineering-focus">Engineering Focus</a> ·
  <a href="#featured-systems--projects">Projects</a> ·
  <a href="#technical-toolkit">Tech Stack</a> ·
  <a href="#get-in-touch">Contact</a>
</p>

---

## About Me

I'm **Hammad Ali Tahir**, a Computer Science graduate from the **University of Education, Lahore**, currently working as an **AI Trainee Engineer Intern at Analytiverse**.

I build AI applications across **Machine Learning, Natural Language Processing, Retrieval-Augmented Generation, and agentic workflows**. My projects connect the full application: preparing documents, retrieving relevant evidence, coordinating model and tool calls, serving streaming responses, and building the interface around them.

My main engineering interest is **making AI answers more dependable**. That means improving retrieval, checking whether the evidence supports a response, handling unsuccessful searches, and tracing what happened when a workflow goes wrong.

> **Current focus:** Generative AI applications, retrieval quality, tool-using agents, and Python backend engineering.

## Engineering Focus

| Focus | How I apply it |
| :--- | :--- |
| **Agentic Workflows** | Build LangGraph workflows with query routing, task decomposition, tool calls, explicit state, and bounded retrieval retries. |
| **Retrieval-Augmented Generation** | Combine dense and keyword search with cross-encoder reranking, chunk grading, query rewriting, and source citations. |
| **Full-Stack AI Applications** | Connect FastAPI backends and Server-Sent Events to React interfaces, authentication, and stored conversations. |
| **Evaluation & Observability** | Evaluate retrieval and answer quality with RAGAS, and inspect execution traces with LangSmith. |
| **Applied Machine Learning** | Build preprocessing pipelines, engineer features, compare classifiers, and evaluate predictive performance. |

---

## Featured Systems & Projects

| Project | Engineering & Architecture | Capabilities | Explore |
| :--- | :--- | :--- | :--- |
| **UOE AI Assistant**<br />Academic RAG application · Final-year project | **Hybrid retrieval** with dense search and BM25, cross-encoder reranking, query rewriting, chunk grading, and retry logic. **FastAPI + SSE** backend connected to **React**, **Pinecone**, **OpenAI**, and **Supabase**. | Answers questions about university curricula and regulations with source-grounded retrieval. Includes conversation history, **RAGAS evaluation**, and **LangSmith tracing**. | [Open Assistant](https://uoe-ai-assistant.vercel.app/chat) |
| **AI Legal Case Manager**<br />Uraan AI Techathon 1.0 | **Ensemble machine learning** for case classification and priority prediction, combined with embedding-based retrieval of relevant judgments. Built with **Python**, **scikit-learn**, and **Streamlit**. | Combines case categorization, triage, and precedent search in one application. | [Open Demo](https://legal-management-system.streamlit.app/) |
| **GitHub Research Agent**<br />Tool-assisted repository research | **LangGraph ReAct workflow** with GitHub tool integrations, repository inspection, caching, and a **React + Vite** chat interface. | Retrieves repository metadata, examines issues and code, and synthesizes findings into research responses. | [Browse Projects](https://github.com/HammadAli08?tab=repositories) |
| **Loan Approval Predictor**<br />End-to-end machine learning | Compares **six classifiers** with column-transformer preprocessing, feature engineering, custom logging, and health monitoring. Packaged with **Docker** for deployment on **Render**. | Connects data preparation, model selection, and prediction serving in a complete application. | [View Repository](https://github.com/HammadAli08/Loan_Approval_Prediction) |

<details>
<summary><strong>Inside UOE AI Assistant — retrieval, reasoning, and evaluation</strong></summary>

### Understanding the question

The workflow routes requests, decomposes questions when necessary, and selects the retrieval path needed to find supporting information.

### Finding useful evidence

Dense search and BM25 keyword search retrieve candidate passages. A cross-encoder reranks them, and chunk grading checks their relevance. Query rewriting and bounded retries help when the initial search does not find enough useful context.

### Delivering the answer

The FastAPI backend streams responses through Server-Sent Events to the React frontend. Supabase supports authentication and conversation history, while source references help users inspect the basis of an answer.

### Inspecting quality

RAGAS supports retrieval and answer evaluation. LangSmith traces make it possible to inspect intermediate steps and investigate failed or slow requests.

</details>

---

## Technical Toolkit

<div align="center">
  <h3>Generative AI, Agents & NLP</h3>
  <p>
    <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph" />
    <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
    <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
    <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
    <img src="https://img.shields.io/badge/Sentence_Transformers-2563EB?style=for-the-badge" alt="Sentence Transformers" />
    <img src="https://img.shields.io/badge/NLTK-154F3C?style=for-the-badge" alt="NLTK" />
  </p>

  <h3>Retrieval, Vector Databases & Storage</h3>
  <p>
    <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge" alt="Pinecone" />
    <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant" />
    <img src="https://img.shields.io/badge/ChromaDB-FFBC00?style=for-the-badge&logoColor=black" alt="ChromaDB" />
    <img src="https://img.shields.io/badge/BM25-334155?style=for-the-badge" alt="BM25" />
    <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black" alt="Supabase" />
    <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  </p>

  <h3>Python, Machine Learning & Data</h3>
  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
    <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
    <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  </p>

  <h3>Backend & Frontend Development</h3>
  <p>
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
    <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
    <img src="https://img.shields.io/badge/Zustand-443E38?style=for-the-badge" alt="Zustand" />
    <img src="https://img.shields.io/badge/SSE_Streaming-0F766E?style=for-the-badge" alt="Server-Sent Events" />
  </p>

  <h3>Evaluation, Deployment & Developer Tools</h3>
  <p>
    <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langsmith&logoColor=white" alt="LangSmith" />
    <img src="https://img.shields.io/badge/RAGAS-7C3AED?style=for-the-badge" alt="RAGAS" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
    <img src="https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white" alt="Fedora Linux" />
    <img src="https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white" alt="Render" />
    <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  </p>
</div>

---

## Beyond the Terminal

Cricket fast bowler and former department team captain. I enjoy historical and geopolitical documentaries, and bring the same interest in strategy and problem-solving to my engineering work.

## Get in Touch

| Find me | Details |
| :--- | :--- |
| **Current Role** | AI Trainee Engineer Intern at **Analytiverse** |
| **Education** | BS Computer Science · University of Education, Lahore · **2026** |
| **Interactive Portfolio** | [fedora-portfolio.vercel.app](https://fedora-portfolio.vercel.app/) |
| **LinkedIn** | [Hammad Ali Tahir](https://www.linkedin.com/in/hammad-ali08/) |
| **Email** | [hammadalitahir8@gmail.com](mailto:hammadalitahir8@gmail.com) |
| **GitHub** | [@HammadAli08](https://github.com/HammadAli08) |

<div align="center">
  <br />
  <p><strong>AI = Logic + Data + Imagination.</strong></p>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3D00FF,50:2563EB,100:00E5FF&height=120&section=footer" alt="" width="100%" />
</div>
