# 🚀 AI Roadmap: 4-Month Plan (Oct 2026 – Feb 2027)

A structured, project-driven plan to become **junior / internship-ready in AI & ML**.
Started: **26 Oct 2026** · Target finish: **14 Feb 2027** (+1 buffer week) · About **15 hrs/week**.

> **Background:** BCA completed, MCA (Sem 2) in progress. Python, OOP and file handling already known, so the plan skips Python basics.
> **Rule:** 70% building, 30% watching/reading. If I watch for two sessions without coding, I switch to building.

---

## 📊 Progress Tracker

| Phase | Weeks | Status |
|---|---|---|
| 1. Data foundations | 1–2 | ⬜ |
| 2. Machine learning + Project 1 | 3–8 | ⬜ |
| 3. Deep learning + Project 2 | 9–11 | ⬜ |
| 4. LLMs, RAG, deployment + Capstone | 12–15 | ⬜ |
| 5. Job readiness | 16 | ⬜ |
| Buffer | 17 | ⬜ |

---

## 🗓️ Week-by-Week Plan

### Phase 1: Data Foundations (Weeks 1–2)
- [ ] **Week 1 (Oct 26 – Nov 1):** NumPy, pandas, data cleaning, EDA → *Deliverable: cleaned and explored dataset notebook on GitHub*
- [ ] **Week 2 (Nov 2 – 8):** SQL and statistics → *Deliverable: SQL practice file + stats notes*

### Phase 2: Machine Learning (Weeks 3–8)
- [ ] **Week 3 (Nov 9 – 15):** Linear and logistic regression → *Regression notebook*
- [ ] **Week 4 (Nov 16 – 22):** Classification, overfitting, regularization, metrics → *Metrics cheat sheet*
- [ ] **Week 5 (Nov 23 – 29):** scikit-learn, pipelines, decision trees → *Kaggle Titanic submission*
- [ ] **Week 6 (Nov 30 – Dec 6):** Ensembles, XGBoost, cross-validation, feature engineering → *Kaggle House Prices submission*
- [ ] **Week 7 (Dec 7 – 13):** **Project 1**: build and tune the model
- [ ] **Week 8 (Dec 14 – 20):** **Project 1**: Streamlit app, deploy, README → *Live prediction app*

### Phase 3: Deep Learning (Weeks 9–11)
- [ ] **Week 9 (Dec 21 – 27):** Neural network basics and PyTorch → *Network trained from scratch*
- [ ] **Week 10 (Dec 28 – Jan 3):** CNNs and transfer learning → *Image classifier*
- [ ] **Week 11 (Jan 4 – 10):** Transformers, Hugging Face, **Project 2** → *Fine-tuned model on GitHub*

### Phase 4: LLMs, RAG & Deployment (Weeks 12–15)
- [ ] **Week 12 (Jan 11 – 17):** LLM APIs and prompting. **Start applying for internships** → *Small LLM script/app*
- [ ] **Week 13 (Jan 18 – 24):** Embeddings, vector databases, RAG → *Basic RAG pipeline*
- [ ] **Week 14 (Jan 25 – 31):** **Capstone** build: RAG app with UI and evaluation
- [ ] **Week 15 (Feb 1 – 7):** FastAPI, Docker, deployment, demo video → *Deployed capstone*

### Phase 5: Job Readiness (Week 16)
- [ ] **Week 16 (Feb 8 – 14):** Polish GitHub, resume, interview prep, applications
- [ ] **Week 17 (Feb 15 – 21):** Buffer / catch-up

---

## 🧱 Projects

| # | Project | Folder | Key skills |
|---|---|---|---|
| 1 | Prediction app (loan / house price / student performance) | `02-project1-ml-app` | scikit-learn, CV, metrics, Streamlit |
| 2 | Fine-tuned image or text classifier | `04-project2-finetuning` | PyTorch, Hugging Face, transfer learning |
| 3 | **Capstone:** "Chat with videos & PDFs" RAG app | `05-capstone-rag-app` | Embeddings, vector DB, LLM APIs, FastAPI, Docker |

Each project README should have: **problem → data → approach → results/metrics → what went wrong → demo link**.

---

## 📚 Online Resources by Phase

### Phase 1: Data foundations
- [Kaggle Learn](https://www.kaggle.com/learn): Pandas, Data Cleaning, Data Visualization, Intro to SQL
- [NumPy absolute beginners guide](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [SQLBolt](https://sqlbolt.com): interactive SQL
- StatQuest with Josh Starmer (YouTube): Statistics Fundamentals playlist

### Phase 2: Machine learning
- Andrew Ng's *Machine Learning Specialization* (Coursera, audit for free)
- Kaggle Learn: Intro to ML, Intermediate ML, Feature Engineering
- StatQuest: Machine Learning playlist
- [scikit-learn user guide](https://scikit-learn.org/stable/user_guide.html)
- 3Blue1Brown: *Essence of Linear Algebra* (first 4 videos)
- Practice: Kaggle Titanic and House Prices competitions

### Phase 3: Deep learning
- 3Blue1Brown: *Neural Networks* series
- Andrej Karpathy: *Neural Networks: Zero to Hero* (micrograd, makemore)
- [PyTorch "Learn the Basics"](https://pytorch.org/tutorials/beginner/basics/intro.html)
- Jay Alammar: *The Illustrated Transformer*
- [Hugging Face LLM Course](https://huggingface.co/learn)

### Phase 4: LLMs, RAG, deployment
- Karpathy: *Intro to Large Language Models* (1-hr talk)
- [DeepLearning.AI short courses](https://learn.deeplearning.ai): Prompt Engineering for Developers, Building Systems with the ChatGPT API, LangChain for LLM Application Development, Building and Evaluating Advanced RAG
- Anthropic and OpenAI API docs and prompt-engineering guides
- Chroma / FAISS (vector DB), sentence-transformers (embeddings), Ollama (free local models)
- [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/) and [Docker Get Started](https://docs.docker.com/get-started/)
- Hosting: Hugging Face Spaces, Render

---

## 📖 Recommended Books

Verify the latest editions and availability before buying. Several have free legal online versions.

### Start with these (core)
| Book | Author(s) | Use it for | When |
|---|---|---|---|
| *Python for Data Analysis* (3rd ed.) | Wes McKinney | pandas and NumPy, by the creator of pandas | Phase 1 |
| *Python Data Science Handbook* | Jake VanderPlas | NumPy, pandas, matplotlib, scikit-learn (free online) | Phase 1–2 |
| *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* (3rd ed.) | Aurélien Géron | Best practical ML book: end-to-end projects | Phase 2–3 |
| *An Introduction to Statistical Learning (with Python)* | James, Witten, Hastie, Tibshirani | ML theory made readable (free PDF) | Phase 2 |
| *Build a Large Language Model (From Scratch)* | Sebastian Raschka | How LLMs actually work, in code | Phase 3–4 |
| *AI Engineering* | Chip Huyen | Building real apps with foundation models: RAG, evaluation, deployment | Phase 4 |

### Strong supplements
| Book | Author(s) | Use it for |
|---|---|---|
| *Practical Statistics for Data Scientists* | Bruce, Bruce & Gedeck | Stats you'll actually use |
| *Dive into Deep Learning* | Zhang, Lipton, Li, Smola | Interactive deep learning with code (free at d2l.ai) |
| *Deep Learning with PyTorch* | Stevens, Antiga & Viehmann | PyTorch in depth |
| *Natural Language Processing with Transformers* | Tunstall, von Werra & Wolf | Hugging Face and transformers |
| *Designing Machine Learning Systems* | Chip Huyen | Production ML, MLOps thinking |
| *Machine Learning Yearning* | Andrew Ng | How to structure ML projects (free) |

### Math and deeper reference (read selectively)
| Book | Author(s) | Notes |
|---|---|---|
| *Mathematics for Machine Learning* | Deisenroth, Faisal & Ong | Linear algebra, calculus, probability (free PDF) |
| *Deep Learning* | Goodfellow, Bengio & Courville | Classic reference (free online); dense, so dip in as needed |

**Suggested reading order:** Python Data Science Handbook → Hands-On ML → ISL → Build an LLM From Scratch → AI Engineering. Read the chapter that matches your current week, not cover to cover.

---

## 🔁 Weekly Routine

| Day | Time | Activity |
|---|---|---|
| Mon–Fri | 1.5–2 hrs | Learn (course/reading) + short exercises |
| Saturday | 4 hrs | Build (projects, Kaggle) |
| Sunday | 3 hrs | Revise, write notes, commit to GitHub |

- Drop to about 5 hrs/week during exams and use the Week 17 buffer.
- If behind schedule, shorten Phase 3 (deep learning), **not** Phase 4 (LLMs and deployment).
- Every Sunday: *"What did I build this week?"*

---

## 📝 Weekly Log

Copy this block into `notes/weekly-log.md` each week.

```
### Week N (dates)
- Planned:
- Completed:
- What I built:
- Blockers / lessons:
- Hours spent:
```

---

## ✅ Definition of Done (by 14 Feb 2027)
- [ ] 3 projects on GitHub with READMEs and demo links
- [ ] 2 Kaggle submissions
- [ ] 1 deployed public app (the capstone)
- [ ] One-page resume, projects first
- [ ] 20+ applications sent (started from Week 12)
