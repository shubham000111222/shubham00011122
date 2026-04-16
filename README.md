<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a1b27&height=120&section=header" width="100%"/>

# Hey, I'm Shubham Kumar 👋

**3rd year CSE @ NIT Delhi · Data Science & ML Enthusiast**

[![Gmail](https://img.shields.io/badge/yshubham0103@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:yshubham0103@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-kumar-288b7437b)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://data-science-portfolio-three-olive.vercel.app)
[![GitHub](https://img.shields.io/badge/shubham000111222-181717?style=flat&logo=github&logoColor=white)](https://github.com/shubham000111222)
[![Location](https://img.shields.io/badge/Delhi,_India-0078D4?style=flat&logo=googlemaps&logoColor=white)](#)

</div>

---

### About me

I'm a third-year Computer Science undergrad at NIT Delhi who loves turning raw data into production-ready ML systems. My work spans the full pipeline — from EDA and feature engineering to model deployment with FastAPI, Docker, and Streamlit.

- 🔭 Currently building end-to-end ML systems with explainability (SHAP, Grad-CAM)
- 🌱 Learning MLOps — Airflow, Docker, CI/CD for ML pipelines
- 💡 Interested in NLP, computer vision, and time-series forecasting
- 🎯 Looking for Data Science / ML internship opportunities

---

### Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**ML / DL**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-00ADD8?style=flat)
![LightGBM](https://img.shields.io/badge/LightGBM-02A86C?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Prophet](https://img.shields.io/badge/Prophet-0072C6?style=flat)

**Tools & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

### Featured projects

<table>
<tr>
<td width="50%" valign="top">

**[🔍 churn-prediction](https://github.com/shubham000111222/churn-prediction)**

XGBoost + LightGBM ensemble with SHAP explainability. Deployed as a REST API via FastAPI and containerized with Docker.

`XGBoost` `LightGBM` `SHAP` `FastAPI` `Docker`

</td>
<td width="50%" valign="top">

**[📈 financial-sentiment](https://github.com/shubham000111222/financial-sentiment)**

FinBERT fine-tuned on 80K financial news headlines. Live sentiment scoring with a Streamlit dashboard + FastAPI backend.

`FinBERT` `HuggingFace` `FastAPI` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[📦 demand-forecasting](https://github.com/shubham000111222/demand-forecasting)**

Prophet + LSTM hybrid model across 1,200 SKUs. Orchestrated with Airflow DAGs, deployed via FastAPI and Docker.

`Prophet` `LSTM` `Airflow` `FastAPI` `Docker`

</td>
<td width="50%" valign="top">

**[🫁 medical-classifier](https://github.com/shubham000111222/medical-classifier)**

EfficientNet-B4 chest X-ray classifier for 14 thoracic conditions with Grad-CAM visual explainability.

`EfficientNet-B4` `Grad-CAM` `FastAPI` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[📚 nitd_pyq](https://github.com/shubham000111222/nitd_pyq)**

NIT Delhi previous year question paper portal — a real tool used by students on campus.

`PHP` `MySQL`

</td>
<td width="50%" valign="top">

**[💰 nitd_crowdfund](https://github.com/shubham000111222/nitd_crowdfund)**

Crowdfunding platform for NIT Delhi student clubs and initiatives.

`PHP` `MySQL`

</td>
</tr>
</table>

---

### GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shubham000111222&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shubham000111222&layout=compact&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

![Streak](https://streak-stats.demolab.com?user=shubham000111222&theme=tokyonight&hide_border=true)

</div>

---

### Contribution activity

<div align="center">

![Snake animation](https://raw.githubusercontent.com/shubham000111222/shubham000111222/output/github-contribution-grid-snake-dark.svg)

</div>

> ☝️ To enable the snake animation, add the GitHub Action below to your profile repo.

---

### GitHub Action to generate the snake (save as `.github/workflows/snake.yml`)

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: shubham000111222
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:0d1117&height=80&section=footer" width="100%"/>

*"Build things that work. Then make them explainable."*

</div>
