# /mnt/data/iarzuakkus_PROFILE_README_clean.md
from pathlib import Path

content = r"""<!-- /iarzuakkus/README.md -->

<h1 align="left">İlayda Arzu Akkuş</h1>

<p align="left">
  Computer Engineer working across artificial intelligence, data and backend development.
  I enjoy building practical systems that connect model development, APIs, databases and usable products.
</p>

<p align="left">
  <a href="https://iarzuakkus.com">
    <img src="https://img.shields.io/badge/iarzuakkus.com-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/i-arzu-akkus">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.kaggle.com/iarzuakkus">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle" />
  </a>
</p>

---

## What I work on

I mainly work on projects involving:

- machine learning and deep learning
- generative AI, RAG and NLP
- data processing and semantic search
- backend APIs and database-driven applications
- spatial data, warehouse systems and optimization

I am especially interested in taking a project beyond the model itself and building the surrounding system needed to make it useful.

---

## Selected projects

### [MemorAI](https://github.com/iarzuakkus/adaptive-rag-project)
A Chrome extension that turns visited web pages into a searchable personal knowledge base.  
It combines semantic chunking, embeddings, FAISS and LLM-based retrieval.

`FastAPI` `FAISS` `Sentence Transformers` `Gemini API` `Chrome Extension`

### [Warehouse Slotting Optimizer](https://github.com/iarzuakkus/warehouse-slotting-optimizer)
Backend infrastructure for carton-based warehouse placement and optimization workflows.

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Docker`

### [BasarSoft Map Application](https://github.com/iarzuakkus/BasarSoft-Backend)
A spatial web application for creating, editing and managing geometry data on an interactive map.

`.NET` `EF Core` `PostGIS` `OpenLayers`

### [Deep Learning Predictions](https://github.com/iarzuakkus/trkcll_deep-learning-predictions)
Deep learning experiments and prediction workflows developed during the Turkcell AI program.

`Python` `Deep Learning` `Model Training` `Prediction`

---

## Tools I use

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="38" height="38" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="38" height="38" alt="C Sharp" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" width="38" height="38" alt=".NET" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="38" height="38" alt="JavaScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="38" height="38" alt="TypeScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="38" height="38" alt="FastAPI" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="38" height="38" alt="PyTorch" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="38" height="38" alt="TensorFlow" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="38" height="38" alt="scikit-learn" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="38" height="38" alt="Pandas" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="38" height="38" alt="NumPy" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="38" height="38" alt="PostgreSQL" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="38" height="38" alt="Docker" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="38" height="38" alt="Git" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="38" height="38" alt="GitHub" />
</p>

**Also:** PostGIS, OpenLayers, REST APIs, SQL, vector databases, web scraping, data visualization and Power BI.

---

## Current interests

<table>
  <tr>
    <td><strong>AI</strong></td>
    <td>RAG, LLM applications, model development, evaluation</td>
  </tr>
  <tr>
    <td><strong>Data</strong></td>
    <td>semantic search, data pipelines, vector search, spatial data</td>
  </tr>
  <tr>
    <td><strong>Backend</strong></td>
    <td>FastAPI, .NET, PostgreSQL, API design</td>
  </tr>
  <tr>
    <td><strong>Engineering</strong></td>
    <td>Docker, MLOps, optimization and production-oriented systems</td>
  </tr>
</table>

---

## Contact

For projects, collaboration or professional opportunities:

<a href="mailto:ilaydaaarzuakkus@gmail.com">
  <img src="https://img.shields.io/badge/Email-333333?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://www.linkedin.com/in/i-arzu-akkus">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://iarzuakkus.com">
  <img src="https://img.shields.io/badge/Portfolio-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" />
</a>
"""

path = Path("/mnt/data/iarzuakkus_PROFILE_README_clean.md")
path.write_text(content, encoding="utf-8")
print(path)
