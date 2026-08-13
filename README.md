# /mnt/data/iarzuakkus_PROFILE_README_final.md
from pathlib import Path

content = r"""<!-- /iarzuakkus/README.md -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=230&text=İlayda%20Arzu%20Akkuş&fontAlign=50&fontAlignY=39&fontSize=46&desc=Computer%20Engineer&descAlign=50&descAlignY=59&descSize=20&color=0:6D28D9,45:9333EA,75:2563EB,100:0891B2&fontColor=ffffff"
    width="100%"
    alt="İlayda Arzu Akkuş"
  />
</p>

<p align="center">
  <a href="https://iarzuakkus.com">
    <img src="https://cdn.simpleicons.org/googlechrome/8B5CF6" width="34" height="34" alt="Portfolio" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/i-arzu-akkus">
    <img src="https://cdn.simpleicons.org/linkedin/0A66C2" width="34" height="34" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.kaggle.com/iarzuakkus">
    <img src="https://cdn.simpleicons.org/kaggle/20BEFF" width="34" height="34" alt="Kaggle" />
  </a>
</p>

<br>

<p align="center">
  I work on artificial intelligence, data-driven systems and backend applications.
  <br>
  My main interest is turning models and ideas into complete, usable software systems.
</p>

<br>

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cs,dotnet,js,ts,fastapi,pytorch,tensorflow,postgres,docker,git,github,vscode&perline=13" alt="Technology stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostGIS" />
  <img src="https://img.shields.io/badge/OpenLayers-1F6B75?style=flat-square" alt="OpenLayers" />
  <img src="https://img.shields.io/badge/FAISS-5B4B8A?style=flat-square" alt="FAISS" />
  <img src="https://img.shields.io/badge/RAG-7C3AED?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/REST%20API-111827?style=flat-square" alt="REST API" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=111111" alt="Power BI" />
</p>

<br>

---

## Selected Work

<table>
<tr>
<td width="50%" valign="top">

### MemorAI

Adaptive RAG system that turns web content into a searchable personal knowledge memory.

<br>

`FastAPI` `FAISS` `Sentence Transformers` `Gemini API`

</td>

<td width="50%" valign="top">

### Warehouse Slotting Optimizer

Warehouse placement and optimization system built around products, cartons, locations and order data.

<br>

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Docker`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Spatial Map Application

Interactive map application for creating, editing and managing geometry data.

<br>

`.NET` `EF Core` `PostGIS` `OpenLayers`

</td>

<td width="50%" valign="top">

### Deep Learning Studies

Model development, training and prediction workflows created during AI-focused training.

<br>

`Python` `Deep Learning` `Model Training` `Data`

</td>
</tr>
</table>

<br>

---

## Areas

<table>
<tr>
<td width="25%" align="center">

### AI

Machine Learning  
Deep Learning  
Generative AI  
NLP  
RAG

</td>

<td width="25%" align="center">

### Data

Data Analysis  
Semantic Search  
Vector Search  
Web Scraping  
Visualization

</td>

<td width="25%" align="center">

### Backend

FastAPI  
.NET  
REST API  
PostgreSQL  
EF Core

</td>

<td width="25%" align="center">

### Spatial

PostGIS  
OpenLayers  
Optimization  
Simulation  
Warehouse Systems

</td>
</tr>
</table>

<br>

---

## GitHub Activity

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=iarzuakkus&show_icons=true&hide_border=true&bg_color=00000000&title_color=A855F7&icon_color=22D3EE&text_color=8B949E"
    height="165"
    alt="GitHub statistics"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=iarzuakkus&layout=compact&hide_border=true&bg_color=00000000&title_color=A855F7&text_color=8B949E"
    height="165"
    alt="Most used languages"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=iarzuakkus&bg_color=00000000&color=8B949E&line=A855F7&point=22D3EE&area=true&hide_border=true"
    width="100%"
    alt="GitHub activity graph"
  />
</p>

<br>

---

<p align="center">
  <a href="mailto:ilaydaaarzuakkus@gmail.com">
    <img src="https://cdn.simpleicons.org/gmail/EA4335" width="32" height="32" alt="Email" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/i-arzu-akkus">
    <img src="https://cdn.simpleicons.org/linkedin/0A66C2" width="32" height="32" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://iarzuakkus.com">
    <img src="https://cdn.simpleicons.org/googlechrome/8B5CF6" width="32" height="32" alt="Portfolio" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.kaggle.com/iarzuakkus">
    <img src="https://cdn.simpleicons.org/kaggle/20BEFF" width="32" height="32" alt="Kaggle" />
  </a>
</p>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0891B2,45:2563EB,75:9333EA,100:6D28D9"
    width="100%"
    alt=""
  />
</p>
"""

path = Path("/mnt/data/iarzuakkus_PROFILE_README_final.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path}")
