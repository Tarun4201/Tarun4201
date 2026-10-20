<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,19,20,24&height=180&section=header&text=Tarun%20N&fontSize=48&fontAlignY=36&desc=Computer%20Science%20Engineer%20%E2%80%94%20Open%20Source%20%7C%20AI%2FML%20%7C%20Full%20Stack&descAlignY=58&fontColor=ffffff" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&pause=1200&color=A855F7&center=true&vCenter=true&width=620&lines=Open+Source+Contributor+%40+Apache+Maven;Building+AI%2FML+platforms+%26+intelligent+agent+systems;Python+%7C+Java+%7C+FastAPI+%7C+React+%7C+PySpark;Bengaluru%2C+India+%F0%9F%87%AE%F0%9F%87%B3+%E2%80%94+Open+to+Opportunities" alt="Typing" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tarun-n-in?utm_source=share_via&utm_content=profile&utm_medium=member_android)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tarunn.9480@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=Tarun4201&style=flat-square&color=7c3aed&label=Profile+Views)](https://github.com/Tarun4201)

</div>

---

## 👋 About Me

I am a **Computer Science & Engineering undergraduate** at **Sai Vidya Institute of Technology, Bengaluru (VTU)** with a strong focus on backend systems, open-source engineering, and applied machine learning.

- 🚀 **Open Source Contributor:** Merged PR into **Apache Maven Core** ([#13239](https://github.com/apache/maven/pull/13239)), solving Windows/Cygwin path resolution bugs.
- 💡 **AI & Systems Builder:** Experienced in building multi-agent marketplaces, Responsible AI explainability platforms, and predictive ML systems.
- 🏆 **Hackathons:** Active member of **Team Code Cosmos**, competed at the **Databricks Offline Hackathon** (MIT Bangalore).
- 🎖️ **Leadership & Discipline:** Former Corporal in the **National Cadet Corps (NCC)** (TSC IGC Firing Camp), district-level cricket player, and marathon runner.

---

## 🌐 Open Source Contributions

### 📦 **[Apache Maven](https://github.com/apache/maven)** — *Core Contributor*
- **Merged PR [#13239](https://github.com/apache/maven/pull/13239)** — Fixed **MNG-8056**: `-f`/`-s` options failing with absolute Cygwin paths, resolving build failures on Windows.
- Traced root cause to the `bin/mvn` launcher script passing unconverted paths to the JVM; implemented a POSIX-to-Windows conversion helper for Cygwin environments.
- Extended the fix to cover all path-accepting flags (`--file`, `--settings`, `--toolchains`, `--at-file`, `--log-file`, etc.) in both space-separated and `=` formats, validated against Maven 3.9.6.

---

## 🛠️ Technical Skills

<div align="center">

| Domain | Technologies & Frameworks |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **Web & Frontend** | ![React](https://img.shields.io/badge/React.js-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **AI / ML & Data** | ![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=flat-square) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-EB5424?style=flat-square) ![Gemini API](https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=googlegemini&logoColor=white) |
| **Databases & Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) |
| **Tools & Platforms** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white) |

</div>

---

## 🚀 Featured Projects

<details open>
<summary><b>🤖 AgentForge — AI-Powered Multi-Agent Marketplace</b></summary>
<br>

*An intelligent multi-agent platform enabling users to discover, deploy, and manage AI agents with intent-based routing.*

- **Stack:** `FastAPI` · `React.js` · `PostgreSQL (Supabase)` · `Gemini API`
- Architected intent classification powered by the Gemini API with modular, prompt-driven agent orchestration.
- Developed robust REST APIs in FastAPI with Supabase PostgreSQL for persistent agent state and user authentication.
- Designed a scalable, clean user interface for managing and testing agent execution flows.

</details>

<details>
<summary><b>⚖️ FairLens — Responsible AI & Model Explainability Platform</b></summary>
<br>

*A Responsible AI auditing platform ensuring model fairness, transparency, and explainability across the ML lifecycle.*

- **Stack:** `Databricks` · `PySpark` · `MLflow` · `XGBoost` · `SHAP`
- Implemented explainability and feature impact analysis using SHAP values to audit bias and fairness.
- Built a **Bronze-Silver-Gold** data lakehouse architecture on Databricks with MLflow for automated experiment tracking.
- Streamlined model evaluation workflows to ensure compliance and transparency before production deployment.

</details>

<details>
<summary><b>🎓 Student Dropout Signal — Early Intervention ML System</b></summary>
<br>

*Machine learning system analyzing academic and behavioral patterns to predict and prevent student dropouts.*

- **Stack:** `Python` · `Machine Learning` · `Data Analytics`
- Engineered predictive feature pipelines from longitudinal academic, attendance, and behavioral data.
- Built and evaluated classification models to identify at-risk students with high recall for timely intervention.
- Designed an intuitive dashboard for educators to visualize risk scores and actionable factors.

</details>

<details>
<summary><b>📈 BullBridge — Stock Market Analysis & Prediction App</b></summary>
<br>

*A beginner-friendly mobile application delivering real-time financial market insights and trend predictions.*

- **Stack:** `React.js` · `Tailwind CSS` · `Android Studio` · `Python` · `Real-time APIs`
- Integrated live market APIs to power interactive stock charts and real-time financial search.
- Incorporated machine learning models for stock trend predictions and sentiment-driven market updates.
- Designed a clean, responsive mobile interface optimized for beginner investors.

</details>

---

## 📅 Contribution Calendar

<div align="center">

<img src="https://ghchart.rshah.org/7c3aed/Tarun4201" alt="Tarun's GitHub Contribution Calendar" width="100%" />

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Tarun4201&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a855f7&icon_color=7c3aed&text_color=94a3b8&rank_icon=github" height="155" alt="Tarun's GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Tarun4201&hide_border=true&background=0d1117&stroke=7c3aed&ring=a855f7&fire=c084fc&currStreakLabel=a855f7&sideLabels=94a3b8&dates=94a3b8" height="155" alt="Tarun's Streak Stats" />

</div>

---

## 🎓 Education

| Institution | Degree / Program | Timeline | Details |
|---|---|---|---|
| **Sai Vidya Institute of Technology, Bengaluru (VTU)** | B.E. in Computer Science & Engineering | 2024 – 2028 | **CGPA: 8.8 / 10** (till 4th Sem) |
| **MVM PU College** | Senior Secondary (XII), Karnataka State Board | 2024 | **Percentage: 80%** (Science) |

---

## 📬 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/tarunn.9480@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tarunn.9480@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/Tarun%20N-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tarun-n-in?utm_source=share_via&utm_content=profile&utm_medium=member_android)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,19,20,24&height=120&section=footer" width="100%" />
