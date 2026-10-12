<h1 align="center">Hi, I'm Mayur More 👋</h1>

<p align="center"><strong>Applied AI · Data Science · Battery Diagnostics · Engineering</strong></p>

Based in Berlin, I bring an electronics and healthcare R&D background to machine learning, analytics, and practical engineering problems. I am studying **MSc Data Science, AI & Digital Business** and **MSc International Business Management** at GISMA University of Applied Sciences.

[Projects](#projects) · [Research](#research--publications) · [Experience](#experience) · [Connect](#connect)

---

### What I work on

**Applied machine learning** for battery health, images, text, and tabular data · **Data storytelling** through analysis and interactive reports · **Engineering systems** that connect sensors, data, and useful decisions

| From industry | From research | From recent coursework |
|:---|:---|:---|
| Battery diagnostics and data logging in healthcare R&D | Coauthored work on battery SOH, a fitness band, and solar tracking | Five projects spanning regression, computer vision, NLP, road safety, and FDA recall analysis |

## Projects

### 🔋 Public project

**[EV lithium-ion battery State of Health estimation](https://github.com/mayurmore0812/ev-lithium-ion-battery-soh-estimation)**  
Research-style documentation of a BTech battery SOH project and related LightGBM publication. It covers charging-data preparation, feature engineering, model evaluation, and the XGBoost/LightGBM approach. **The public repository documents the work; its implementation code and notebooks are private.**

### 🧠 Recent data science projects

<sub>These public repositories document the projects while their notebooks, data, and other files are prepared for release.</sub>

<details>
<summary><strong>🚕 NYC taxi trip duration prediction · tabular machine learning</strong></summary>

Built a regression workflow with trip-time, distance, bearing, airport, and location-zone features. Compared Ridge, Random Forest, and histogram gradient boosting models, with validation-based selection and duration-group error analysis. The project uses the labelled NYC Taxi Trip Duration competition data.

<em>Python · pandas · scikit-learn · geospatial feature engineering</em>

**Repository:** [View project on GitHub ↗](https://github.com/mayurmore0812/nyc-taxi-trip-duration)

</details>

<details>
<summary><strong>🛣️ Great Britain road accident severity · exploratory analysis</strong></summary>

Analysed about **1.78 million recorded accidents from 2005–2015**, joining accident, vehicle, and casualty data at the correct level to avoid double counting. Compared accident volume with the share of recorded cases classified as serious or fatal, then turned ten questions into charts and road-safety recommendations.

<em>Python · pandas · seaborn · data visualisation</em>

**Repository:** [View project on GitHub ↗](https://github.com/mayurmore0812/gb-road-accident-severity-analysis)

</details>

<details>
<summary><strong>🔍 PCB component placement inspection · computer vision</strong></summary>

Fine-tuned an ImageNet-pretrained MobileNetV2 to classify acceptable versus incorrect component placement. The saved experiment reports **0.853 balanced accuracy on 34 held-out images** and detects **15 of 17 incorrect placements**. The evaluation uses new images of board designs represented during training; the system is an inspection-support prototype.

<em>TensorFlow/Keras · transfer learning · image preprocessing</em>

**Repository:** [View project on GitHub ↗](https://github.com/mayurmore0812/pcb-placement-classification)

</details>

<details>
<summary><strong>📄 PDF context compression · NLP and summarisation</strong></summary>

Built a PDF-to-Markdown pipeline with section detection, sentence selection, source extracts, and a pretrained BART rewriter. Compared TF-IDF with logistic regression against frozen sentence embeddings with a bidirectional GRU, using ranking, ROUGE, calibration, and token reduction to assess different parts of the system.

<em>PyTorch · Hugging Face · scikit-learn · PDF processing</em>

**Repository:** [View project on GitHub ↗](https://github.com/mayurmore0812/pdf-context-compression)

</details>

<details>
<summary><strong>🍽️ FDA food recall review · interactive data storytelling</strong></summary>

Reconciled **22,840 product records into 5,875 distinct recall events** and built ten management-focused insights on workload, severity, issue categories, firm locations, initial notification methods, and recorded status. A separate interactive Plotly edition adds filters and a geographic view. The data is a historical snapshot, so its counts do not describe current recall status or consumer risk.

<em>pandas · Plotly · data reconciliation · dashboard design</em>

**Repository:** [View project on GitHub ↗](https://github.com/mayurmore0812/fda-food-recall-analysis)

</details>

### ⚙️ Earlier engineering and team projects

<details>
<summary><strong>Battery diagnostics, IoT, wearables, and solar tracking</strong></summary>

- **Battery health diagnostic prototype:** At Philips India, developed a Python-based proof of concept for Energy Storage Unit diagnostics, with structured data logging and analysis to support service decisions.
- **IoT lab automation:** Built a connected lab-system concept using microcontrollers, Raspberry Pi, and Firebase, described in my earlier profile.
- **Fitness tracking band:** Co-developed a wearable that tracks steps, jumps, and kicks. I worked on the ESP-based hardware, device logic, and Firebase connection; teammates contributed the Flutter app, enclosure, and data collection.
- **Sun Flora solar tracker:** Coauthored an 8051 assembly-language dual-axis solar-tracking project using light sensors, motor control, and an LCD.

</details>

### 🧩 Recent challenges

- **Huawei TechArena 2026, Digital Power (CellScale):** Worked on LFP battery SOH trajectories and end-of-life prediction from cycling time series; qualified for the Nuremberg on-site ceremony.
- **Huawei TechArena 2026, 3D-Matters:** Team entry on anatomical ear landmarks from 3D head scans, using a DiffusionNet ensemble and anatomical post-processing.

<details>
<summary><strong>Earlier recognition</strong></summary>

- **Aavishkar 2023–24:** Qualified for the University of Mumbai final round, as listed in my CV.
- **Persona Fest 2020:** Second place, as listed in my CV.
- **PROTECH 2020:** First place, as listed in my CV.

</details>

## Research & publications

These are **coauthored** publications. The battery patent is listed in my CV; I have not linked a registry record here.

| Work | Publication |
|:---|:---|
| [EV Lithium-Ion Battery SOH Estimation Based on LightGBM Model](https://doi.org/10.1007/978-981-97-8160-7_6) | Springer Nature, *Intelligent Systems / ICMIB 2024 proceedings* (2025) |
| [The Fitness Tracker Band](https://doi.org/10.1063/5.0291757) | AIP Conference Proceedings (2025) |
| [Sun Flora: Dual Axis Solar Tracker Using 8051 in Assembly Language](https://doi.org/10.56726/IRJMETS46906) | IRJMETS (2023) |

**Granted patent listed in my CV:** “A System and Method for Calculation of State of Health of Li-Ion Battery” (SA Patents, 2024; registry record not yet linked).

## Experience

| Role | What I worked on |
|:---|:---|
| **Philips India Limited** · Image Guided Therapy R&D apprentice/intern · Apr 2024–Jun 2025 | Battery diagnostic proof of concept, data logging, diagnostic automation, and production fault investigation |
| **Nitya Innovations LLP** · Data Analyst Intern · Jan–Jun 2024 | EV battery SOH data preparation, feature engineering, and XGBoost/LightGBM modelling |
| **Bunnyfied Labs Pvt. Ltd.** · Junior Data Analyst & ML Developer · Apr 2023–Jan 2024 | Résumé-to-job matching prototype, LLM prompt evaluation, Power BI dashboards, and reporting automation |

<details>
<summary><strong>Education and tools</strong></summary>

**Education**

- GISMA University of Applied Sciences, Berlin — MSc Data Science, AI & Digital Business + MSc International Business Management (2025–2027)
- Vishwakarma Institute of Information Technology, Pune — BTech Electronics & Telecommunication Engineering (2024)
- Cusrow Wadia Institute of Technology, Pune — Diploma in Electronics & Telecommunication Engineering (2021)

**Tools I have used**

- **Data and ML:** Python, SQL, pandas, NumPy, scikit-learn, TensorFlow/Keras, PyTorch, XGBoost, LightGBM
- **Analysis and communication:** Power BI, Plotly, matplotlib, seaborn, Excel
- **Engineering:** MATLAB, Arduino, ESP8266, Raspberry Pi, Firebase
- **NLP:** TF-IDF, sentence embeddings, Hugging Face models, LLM APIs

</details>

## Connect

[LinkedIn](https://www.linkedin.com/in/mayurmore0812) · [Email](mailto:mayurmore0812@gmail.com) · [GitHub](https://github.com/mayurmore0812)

<sub>Project descriptions cover academic and prototype work. Source files will be added to the project repositories when they are ready to share.</sub>
