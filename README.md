<h1 align="center">Hi, I'm Lahari 👋</h1>
<p align="center">
  <em>Data Science grad student at IU Bloomington &nbsp;|&nbsp; Ex-SWE at SAP &nbsp;|&nbsp; ML &nbsp;|&nbsp; Full Stack &nbsp;|&nbsp; Distributed Systems</em>
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=laharigandrapu&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### About Me

I spent 2.5 years at SAP building internal tools that engineering and ops teams actually used in production. That meant caring about things beyond whether code ran locally: incident resolution times, SLA compliance, provisioning pipelines, migration tooling. I reduced data center provisioning from 10 hours to 1 hour by automating 7 manual steps, and cut customer migration time from weeks to 2 hours by building a Node.js CLI that batch converted 500+ legacy artifacts.

I am now finishing my MS in Data Science at Indiana University Bloomington, using that background to build ML systems the same way: with production constraints in mind, not just accuracy numbers.

Most recently I built an agentic RAG system for intelligent document querying. A LangGraph state machine routes and decomposes complex questions, retrieves from Qdrant using sentence-transformers embeddings, and streams cited answers in real time via SSE. Deployed on Google Cloud Run with a full GitHub Actions CI/CD pipeline. Before that I built a computer vision pipeline at MyEdMaster that reduced body measurement entry time from 2 minutes to 6 seconds using MediaPipe and ResNet-50. Before that I built an AI travel planner where 6 LLM powered agents run in parallel using Celery and Redis, cutting trip planning time from 2 hours to 5 minutes.

---

### What I Have Built

**Agentic RAG DocQuery:** Production-grade document intelligence platform. A LangGraph state machine routes queries, decomposes complex questions into sub-questions, retrieves from Qdrant using sentence-transformers embeddings, and synthesizes cited answers with a full hop trace. Supports PDF, DOCX, Markdown, plain text, and URLs. Real-time token streaming via SSE. Switchable LLM providers (Groq, Gemini, Mistral) mid-session. Deployed on Google Cloud Run with GitHub Actions CI/CD.

**AI Agentic Travel Planner:** 6 LLM agents (Claude + OpenAI) coordinated via Celery and Redis. Parallel execution cut end to end planning latency by 75%. Trip planning time went from 2 hours to 5 minutes.

**Room Reservation System:** Microservices platform built for 1M+ concurrent users, scaling to 5M on Kubernetes. 15+ REST APIs, JWT auth, RabbitMQ async workflows, 100% unit test coverage with JUnit 5 and Mockito.

**Body Measurement CV Pipeline:** Real time pose detection with MediaPipe and ResNet-50. 90% detection accuracy across varied lighting and body types. 87% reduction in measurement entry time.

---

### What I Work With

Python, Java, JavaScript, TypeScript. Used for both backend and ML work.

For ML: PyTorch, TensorFlow, scikit-learn, LangChain, LangGraph, OpenAI and Claude APIs, OpenCV, MediaPipe.

For backend and infra: Spring Boot, Flask, FastAPI, Node.js, Docker, Kubernetes, AWS (Lambda, S3, EC2, ECS), GCP (Cloud Run), RabbitMQ, Redis, Qdrant, PostgreSQL.

---

### Let's Connect

Email: [laharigandrapu11@gmail.com](mailto:laharigandrapu11@gmail.com)  
LinkedIn: [linkedin.com/in/laharigandrapu](https://linkedin.com/in/laharigandrapu)  
GitHub: [github.com/laharigandrapu11](https://github.com/laharigandrapu11)
