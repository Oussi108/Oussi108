<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="El Houcine Oussi – machine learning for solar power forecasting" width="100%">
</picture>

<br><br>

<a href="mailto:oussi108@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://www.linkedin.com/in/el-houcine-oussi-5abb8a1b7"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://el-houcine-oussi.web.app/"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
<!-- Add when ready:
<a href="https://www.kaggle.com/oussielhoucine"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"></a>
<a href="https://orcid.org/0000-0000-0000-0000"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
<a href="https://scholar.google.com/citations?user=XXXX"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
-->

### 🎓 Seeking a fully funded PhD position from 2027 in solar and renewable energy forecasting

</div>

---

## 👋 About me

I'm an M.Sc. student in Computer Science at **Nanjing University of Information Science and Technology (NUIST)**, China.
My research asks a practical question: **which learned solar forecasts actually beat simple references, at which horizon,
and when does better accuracy turn into better decisions?**

- 🔭 **Now:** running the final held-out test of a 4–6 h satellite + weather-forecast model for 50 Australian solar farms
- 🛠️ **Background:** software engineer (C#/.NET, Java, Flutter) turned forecasting researcher
- 🌍 **Languages:** Arabic · English · French · Mandarin (HSK 3)

## 🔬 Research at a glance

| | Study | Horizon | Data | Status |
|:--:|---|:--:|---|:--:|
| ☁️ | **Sky-image nowcasting** – do sky images add value beyond recent PV history? | 5–30 min | Stanford SKIPP'D | ![experiments complete](https://img.shields.io/badge/experiments-complete-6f42c1?style=flat-square) |
| 🛰️ | **Solar farms up to 6 h ahead** with Himawari / Meteosat imagery and issued weather forecasts | 0.5–6 h | 50 Australian solar farms (AEMO) · 94 UK virtual farms | ![final test running](https://img.shields.io/badge/final%20test-running-f59e0b?style=flat-square) |
| 📈 | **Reference specification and model updating** – how much do references, retraining and calibration change measured skill? | 2–12 h | DKASC Alice Springs · 31 HKUST rooftops · NREL PVDAQ 9068 | ![manuscript ready](https://img.shields.io/badge/manuscript-ready-2ea44f?style=flat-square) |
| 🔋 | **From forecast quality to value** – probabilistic forecasts for home-battery scheduling | day-ahead | 91,290 simulated scenarios · 40 Ausgrid households | ![manuscript ready](https://img.shields.io/badge/manuscript-ready-2ea44f?style=flat-square) |

### How the studies fit together

```mermaid
flowchart LR
    A["☁️ Sky images<br/>5–30 min"] --> B["🛰️ Satellite + weather forecasts<br/>0.5–6 h"]
    B --> C["📈 Ground observations<br/>2–12 h"]
    C --> D["🔋 Battery scheduling<br/>day-ahead value"]
    classDef horizon fill:#FFF4DE,stroke:#E8890C,color:#1F2937
    classDef value fill:#E8F1FB,stroke:#2563EB,color:#1F2937
    class A,B,C horizon
    class D value
```

From minutes to a day ahead: which inputs help at which horizon, and when forecast accuracy becomes operational value.

<details>
<summary><b>💡 Findings so far</b> (click to open)</summary>
<br>

- Specifying the smart-persistence reference correctly cut reported skill at the Hong Kong testbed from **54–57% to 7–13%**.
- Monthly retraining gave six-hour gains over previous-day persistence of **+6.9%** (HKUST) and **+10.0%** (PVDAQ 9068, 2023).
- A battery scheduler that uses the full forecast distribution **lowered cost for all 40 real households** tested.
- Sky images gave **no established gain** over a PV-history LightGBM model on SKIPP'D – a negative result I report as one.

</details>

## 🧪 How I work

| 🔒 Fixed plans | 📏 Honest statistics | ♻️ Reproducible code |
|---|---|---|
| Analysis plans written before the final test; held-out test sets scored once | Paired bootstrap confidence intervals, Holm correction, negative results kept | pytest suites, checksum manifests, pinned environments |

## 🧰 Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,git,github,docker,cs,dotnet,java,flutter,django,react,angular&perline=12" alt="Python, PyTorch, Git, GitHub, Docker, C#, .NET, Java, Flutter, Django, React, Angular">
</p>

![LightGBM](https://img.shields.io/badge/LightGBM-2C7BB6?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab%20GPUs-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![pvlib](https://img.shields.io/badge/pvlib-E8890C?style=flat-square)
![Satellite data](https://img.shields.io/badge/Himawari%20%7C%20Meteosat%20SEVIRI-0F766E?style=flat-square)
![NWP](https://img.shields.io/badge/NWP%20%28GRIB%29%20%7C%20ERA5-334155?style=flat-square)

## 📝 Manuscripts

- **Reference specification, model updating and calibration population in hourly photovoltaic power forecasting** – manuscript prepared for submission (2026)
- **When do probabilistic solar forecasts earn their keep? Forecast quality, distributional validity and operational value in behind-the-meter battery scheduling** – manuscript complete (2026)

## 📂 Code

Code for each study will be published here together with its paper.
Earlier software projects: [HomeRealm](https://github.com/Oussi108/HomeRealm) · [Project_petshop_JEE](https://github.com/Oussi108/Project_petshop_JEE) · [taskwithauthdotnet](https://github.com/Oussi108/taskwithauthdotnet)

---

<div align="center">
<sub>Open to PhD positions, research collaborations and questions about solar forecasting – feel free to reach out.</sub>
</div>
