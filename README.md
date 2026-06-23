<div align="center">

# Hi, I'm Anish Laddha

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=B.Tech%20CSE%20%40%20LNMIIT%20Jaipur%3BBuilding%20RAG%20pipelines%20and%20multi-agent%20systems%3BFull-stack%20developer%20%7C%20Backend%20%26%20Infrastructure%3BResearching%20Small%20Language%20Models%20as%20Judges%3BData%20Science%20Intern%20%40%20Deloitte" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anish-laddha/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anshladdha15@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=anishh15&label=Profile%20Views&color=0e75b6&style=for-the-badge)

</div>

---

## About Me

- B.Tech in Computer Science and Engineering at **LNM Institute of Information Technology (LNMIIT), Jaipur** (Aug 2023 to May 2027)
- CGPA 9.38/10, Merit Scholarship for 6 consecutive semesters
- Interested in small language models, retrieval-augmented generation, multi-agent systems, and backend/infrastructure engineering
- Data Science Intern at **Deloitte**, building RAG pipelines for automated document validation
- Competitive programming: 430+ DSA problems solved, LeetCode Knight badge (1,881 rating)

---

## Currently

- Building RAG (Retrieval-Augmented Generation) pipelines for automated structured-document validation at Deloitte (Jun to Aug 2026)
- Co-authoring two papers targeting **EMNLP 2026**: *SLMJury* is live on arXiv, the companion survey is in submission
- Maintaining `slmjury`, a pip-installable package for evaluating small language models as judges

---

## Research

### SLMJury: Can Small Language Models Judge as Well as Large Ones?
*Anish Laddha, Nitesh Pradhan, Gaurav Srivastava / arXiv:2606.07810 / Submitted to ACL ARR, target EMNLP 2026*

[![arXiv](https://img.shields.io/badge/arXiv-2606.07810-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2606.07810)
[![GitHub](https://img.shields.io/badge/GitHub-SLMJury-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/anishh15/SLMJury)
[![PyPI](https://img.shields.io/badge/PyPI-slmjury-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/slmjury/)
[![Leaderboard](https://img.shields.io/badge/Leaderboard-Live_Demo-4ECDC4?style=flat-square)](https://anishh15.github.io/SLMJury/)

Benchmarked 16 SLM judges (0.6B to 14B parameters, across the Qwen, Llama, and Phi-4 families) on 10 datasets, 64,824+ judgments per configuration, to test whether small models can stand in for large proprietary judges.

- A 14B Phi-4 judge reaches 89.55% binary-judgment accuracy; a 3-model majority-vote ensemble nudges that to 89.61%
- "Overthinking" turns out to be domain-dependent: quick 10-token verdicts match or beat long chain-of-thought reasoning on math judging, while reasoning wins on general-knowledge tasks by up to 23%
- Multi-agent debate (Reflect-Critique-Refine) hurts accuracy in every configuration tested
- Scaled to 3,900+ experiment configurations on 4xV100 GPUs with multi-GPU vLLM pipelines, GPTQ quantization, and tensor parallelism

### Small Language Models as Judges: A Survey
*Anish Laddha, Nitesh Pradhan, Gaurav Srivastava / Submitted to ACL ARR, target EMNLP 2026*

[![Website](https://img.shields.io/badge/Website-Live_Demo-4ECDC4?style=flat-square)](https://anishh15.github.io/Awesome-SLM-as-a-Judge/)
[![Paper](https://img.shields.io/badge/Paper-PDF-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://anishh15.github.io/Awesome-SLM-as-a-Judge/paper.pdf)
[![GitHub](https://img.shields.io/badge/GitHub-Awesome--SLM--as--a--Judge-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/anishh15/Awesome-SLM-as-a-Judge)

A companion survey curating 60+ papers on the SLM-as-a-judge paradigm across a five-part taxonomy: background and motivation, individual SLM judging, multi-agent strategies, benchmarks and metrics, and open challenges. Not yet on arXiv; the full text and interactive figures live on the companion site above.

---

## Pinned Repositories

<div align="center">
  <a href="https://github.com/anishh15/SLMJury">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=anishh15&repo=SLMJury&theme=tokyonight&hide_border=true" />
  </a>
  <a href="https://github.com/anishh15/Awesome-SLM-as-a-Judge">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=anishh15&repo=Awesome-SLM-as-a-Judge&theme=tokyonight&hide_border=true" />
  </a>
  <a href="https://github.com/anishh15/ArxivAssistant">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=anishh15&repo=ArxivAssistant&theme=tokyonight&hide_border=true" />
  </a>
  <a href="https://github.com/anishh15/intelligent-content-moderation">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=anishh15&repo=intelligent-content-moderation&theme=tokyonight&hide_border=true" />
  </a>
</div>

---

## Featured Projects

### [Multimodal Content Moderation System](https://github.com/anishh15/intelligent-content-moderation)

A full-stack content moderation platform that pairs text toxicity detection with image NSFW detection and cross-modal correlation to catch what single-modality filters miss.

- 98% text accuracy (RoBERTa toxicity classifier) and 96% image accuracy (Falconsai NSFW detector), backed by a HuggingFace > OpenAI > keyword fallback chain
- Sub-20ms cached response time vs. 200-500ms live, via Redis caching, 4-tier rate limiting, JWT auth, and RBAC
- Full Docker Compose stack: Express backend, React 19 admin dashboard, MongoDB, Redis, behind nginx reverse proxy, deployed on Render

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)

### [ArxivAssistant](https://github.com/anishh15/ArxivAssistant)

A RAG-based research paper navigator that pulls papers live from arXiv (no pre-loaded corpus) and answers questions with grounded source citations.

- Two-pass arXiv search (title match, then keyword fallback with deduplication), plus direct arXiv-ID lookup
- Full-PDF text extraction via PyMuPDF (falls back to abstracts when unavailable), chunked and embedded locally with `all-MiniLM-L6-v2`
- FAISS similarity search feeding a LangChain retrieval chain over Qwen2.5-7B-Instruct: entirely free components, no paid APIs or cloud vector databases

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-00758F?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### [slmjury](https://github.com/anishh15/SLMJury)

A pip-installable Python package for evaluating small language models as judges. Published on PyPI and integrated with the SLMJury research codebase.

- Provides a CLI and Python API for running SLM-as-a-judge evaluations out of the box
- Supports multiple judging strategies: single-model, majority voting, and multi-agent debate
- CI/CD pipeline via GitHub Actions for automated testing and PyPI publishing

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![vLLM](https://img.shields.io/badge/vLLM-FF6B6B?style=flat-square) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

---

## Experience

| Role | Company | Duration |
|---|---|---|
| Data Science Intern | Deloitte | Jun 2026 to Aug 2026 |
| Software Engineering Intern | Times Network | May 2025 to Jul 2025 |

- **Deloitte**: Building advanced RAG pipelines for automated validation of structured documents.
- **Times Network**: Cut editorial review effort by 80% (validated on 100+ articles) with a GPT-4-powered Streamlit app (OpenAI API, SerpAPI, BeautifulSoup) that automated competitor news comparisons across 4 broadcast sources. Separately, predicted expert smartphone-review scores across 6 categories with R² = 0.97-0.98, validated by the Digit.in editorial team, using a multi-output regression pipeline with feature engineering on 300 internal device records.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-FF6B6B?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00758F?style=flat-square)
![Chroma](https://img.shields.io/badge/Chroma-4A154B?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0E76A8?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Data**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat-square)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-8B8B00?style=flat-square)

**Web & Backend**

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![REST APIs](https://img.shields.io/badge/RESTful_APIs-005571?style=flat-square)
![Asyncio](https://img.shields.io/badge/Asyncio-3776AB?style=flat-square&logo=python&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anish-laddha/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anshladdha15@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anishh15)

<p align="center"><em>Open to conversations about small language models, RAG systems, backend engineering, or anything systems-related. Reach out anytime.</em></p>

</div>