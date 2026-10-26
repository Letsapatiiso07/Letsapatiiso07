# Tiiso Letsapa

**Data Engineer | Machine Learning** · Pretoria, South Africa

[LinkedIn](https://www.linkedin.com/in/tiiso-letsapa-664990209) · [Letsapamyron07@gmail.com](mailto:Letsapamyron07@gmail.com)

I build data pipelines and machine learning models, and I test them on real
data where I can: real loan records, real electricity prices, real
radiotherapy plans. Each project's README says where the data comes from,
how to run the code, and what it does not do yet.

## Featured projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/Radiosurgery-Dose-Explorer"><b>Radiosurgery Dose Explorer</b></a><br>
<a href="https://github.com/Letsapatiiso07/Radiosurgery-Dose-Explorer"><img src="https://raw.githubusercontent.com/Letsapatiiso07/Radiosurgery-Dose-Explorer/main/results/segmentation_cases.png" alt="The doctors' tumour outline and the AI's outline on three MRI scans of test patients"></a><br>
A 3D U-Net that outlines a brain tumour on MRI, scoring a Dice of 0.934 against the doctors' outlines on 60 patients it never saw. It also measures 59 real Gamma Knife plans from their 3D dose and predicts the hearing organ's dose with machine learning.<br>
<sub>Python · PyTorch · pydicom · SciPy · scikit-learn · <a href="https://letsapatiiso07.github.io/Radiosurgery-Dose-Explorer/">live viewer</a></sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/Credit-Risk-Assessment"><b>Credit Risk Assessment</b></a><br>
<a href="https://github.com/Letsapatiiso07/Credit-Risk-Assessment"><img src="https://raw.githubusercontent.com/Letsapatiiso07/Credit-Risk-Assessment/main/images/roc_curve.png" alt="ROC curve of the loan default model, AUC 0.947"></a><br>
Predicts loan default on 32,581 real loans. On a held-out test set: ROC AUC 0.947, and 97% of the loans it flags do default.<br>
<sub>Python · scikit-learn · XGBoost · pandas</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/bess-optimization"><b>Battery Dispatch Optimisation</b></a><br>
<a href="https://github.com/Letsapatiiso07/bess-optimization"><img src="https://raw.githubusercontent.com/Letsapatiiso07/bess-optimization/main/bess_optimization_results.png" alt="Prices, state of charge and battery dispatch over three days"></a><br>
A linear program for a 100 MW / 200 MWh battery trading real South Australian 5-minute prices. Best possible revenue over three days: $322,987, with 69% from one price spike.<br>
<sub>Python · SciPy (HiGHS) · pandas</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/aws-weather-pipeline"><b>AWS Weather Pipeline</b></a><br>
<a href="https://github.com/Letsapatiiso07/aws-weather-pipeline"><img src="https://raw.githubusercontent.com/Letsapatiiso07/aws-weather-pipeline/main/docs/architecture.png" alt="EventBridge triggers Lambda, which writes to S3 and DynamoDB"></a><br>
A Lambda function on a 15-minute schedule pulls the weather for four South African cities and stores raw JSON in S3 and clean records in DynamoDB.<br>
<sub>AWS Lambda · EventBridge · S3 · DynamoDB · Python</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/mining_analyzer"><b>Mine Sites from Sentinel-2</b></a><br>
<a href="https://github.com/Letsapatiiso07/mining_analyzer"><img src="https://raw.githubusercontent.com/Letsapatiiso07/mining_analyzer/main/docs/Tharisa_Platinum_change.png" alt="Tharisa mine in 2017 and 2026 from Sentinel-2, with bare ground change"></a><br>
Tracks bare ground at five South African mine sites from free Sentinel-2 images, 2017 to 2026. At the Tharisa platinum mine it grew from 7.9 to 9.8 km².<br>
<sub>Python · rasterio · STAC · Streamlit</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/wind-turbine-optimizer"><b>Wind Turbine Blade Optimiser</b></a><br>
<a href="https://github.com/Letsapatiiso07/wind-turbine-optimizer"><img src="https://raw.githubusercontent.com/Letsapatiiso07/wind-turbine-optimizer/main/docs/baseline_vs_reference.png" alt="BEM model of the NREL 5 MW turbine against NREL reference power, Cp and thrust curves"></a><br>
A blade element momentum model of the NREL 5 MW turbine that matches NREL's published yearly energy within 0.6%, then reshapes the blade within load limits for a measured gain of 0.44%.<br>
<sub>Python · SciPy · PyTorch · pymoo · Streamlit</sub>
</td>
</tr>
</table>

## More highlights

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/dataops-studio"><b>DataOps Studio</b></a><br>
<a href="https://github.com/Letsapatiiso07/dataops-studio"><img src="https://raw.githubusercontent.com/Letsapatiiso07/dataops-studio/main/docs/dashboard.png" alt="Dashboard with pipeline latency, dataset size and model success charts"></a><br>
A front-end prototype of a data team dashboard: pipeline runs, a searchable dataset catalog and a model registry, on sample data.<br>
<sub>React · TypeScript · Tailwind CSS · Recharts</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/realtime-iot-etl-pipeline"><b>Real-Time IoT ETL Pipeline</b></a><br>
<a href="https://github.com/Letsapatiiso07/realtime-iot-etl-pipeline"><img src="https://raw.githubusercontent.com/Letsapatiiso07/realtime-iot-etl-pipeline/main/docs/dashboard.png" alt="Live dashboard of sensor readings and anomalies"></a><br>
Stream-style ETL in plain Python: six simulated sensors, anomaly flags from a rolling z-score, SQLite storage and a live web dashboard.<br>
<sub>Python standard library · SQLite · threads and queues</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/renewable-energy-forecasting-dashboard"><b>Renewable Energy Forecasting</b></a><br>
<a href="https://github.com/Letsapatiiso07/renewable-energy-forecasting-dashboard"><img src="https://raw.githubusercontent.com/Letsapatiiso07/renewable-energy-forecasting-dashboard/main/docs/dashboard.png" alt="Dashboard with held-out scores and a 7-day solar and wind forecast"></a><br>
Day-ahead solar and wind forecasts for three South African sites from ECMWF weather. On a held-out year it beats a physical baseline by 6.9% for solar and 4.8% for wind. Plant output is modelled, not measured.<br>
<sub>Python · XGBoost · pvlib · FastAPI · React</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Letsapatiiso07/medical-image-analysis"><b>Pneumonia on Chest X-rays</b></a><br>
<a href="https://github.com/Letsapatiiso07/medical-image-analysis"><img src="https://raw.githubusercontent.com/Letsapatiiso07/medical-image-analysis/main/docs/gradcam_examples.png" alt="Grad-CAM heatmaps on four test chest X-rays"></a><br>
A small CNN on 5,856 real paediatric chest X-rays: test AUC 0.96 against 0.50 for a baseline, with Grad-CAM showing where the model looked. A learning project, not a diagnostic tool.<br>
<sub>Python · TensorFlow · scikit-learn</sub>
</td>
</tr>
</table>

## More projects

| Project | What it is |
|---|---|
| [F1 Race Winner Prediction](https://github.com/Letsapatiiso07/f1-race-winner-prediction) | Predicts race winners from the grid and earlier results only; right in 65.7% of 2023 to 2025 races, against 58.6% for "the pole sitter wins" |
| [Airfoil Optimisation](https://github.com/Letsapatiiso07/airfoil-optimization) | Vortex panel method and boundary-layer drag checked against NACA 0012 data, with ML surrogates and a genetic algorithm |
| [Pothole Detector](https://github.com/Letsapatiiso07/pothole-detector) | Classifies dash-cam frames from South African roads, tested on recording sessions it never saw |
| [Stock Analytics Dashboard](https://github.com/Letsapatiiso07/stock-analytics-dashboard) | Daily stock pipeline and Streamlit app that tests next-day forecasts walk-forward; the models do not beat the naive baseline, and the app says so |
| [COVID-19 Data Tracker](https://github.com/Letsapatiiso07/COVID-19-Data-Tracker) | Notebook comparing cases, deaths and vaccinations in Kenya, the US and India, from Our World in Data |
| [Crypto Pipeline with Airflow](https://github.com/Letsapatiiso07/Data-Pipeline-with-ApacheAirflow) | Hourly Airflow DAG that pulls Bitcoin and Ethereum market data into CSV files |
| [Sales Analytics Pipeline](https://github.com/Letsapatiiso07/sales-analytics-pipeline) | Databricks notebook: quality checks, transforms, customer segments and KPIs on generated sales data |
| [Crypto Chatbot](https://github.com/Letsapatiiso07/crypto-chatbot) | Command-line bot for live crypto prices from the CoinGecko API |
| [Library Management System](https://github.com/Letsapatiiso07/library-management-system) | MySQL schema with 10 tables, sample data and reporting views |

## Skills

- **Languages:** Python, SQL, TypeScript
- **Data engineering:** pandas, Apache Airflow, AWS (Lambda, EventBridge, S3, DynamoDB), Databricks, FastAPI, SQLite, MySQL
- **Machine learning and statistics:** scikit-learn, XGBoost, PyTorch, TensorFlow, time-series backtesting, model evaluation, bootstrap confidence intervals
- **Engineering and geospatial:** SciPy, linear programming, genetic algorithms, BEM and panel methods, pvlib, Sentinel-2 imagery (STAC, rasterio)
- **Front end and charts:** React, Streamlit, Tailwind CSS, Recharts, Matplotlib

## Certifications and education

| Certification or qualification | Provider | Year |
|---|---|---|
| Diploma in Financial Management | Regent Business School | 2025 |
| Data Engineer Professional | DataCamp | 2025 |
| Associate Data Engineer | DataCamp | 2025 |
| SQL Associate | DataCamp | 2025 |
| Machine Learning Engineer | DataCamp | 2025 |
| AI Engineer for Data Scientists Associate | DataCamp | 2025 |
| IT Automation with Python | Google | 2025 |
| Azure Solutions Architect | Microsoft | 2025 |
| Azure AI Engineer Associate | Microsoft | 2025 |
| Azure Data Scientist Associate | Microsoft | 2025 |
| Fabric Data Engineer Associate | Microsoft | 2026 |

## Contact

Open to data engineering and machine learning roles, including remote and
hybrid. The quickest way to reach me is
[email](mailto:Letsapamyron07@gmail.com) or
[LinkedIn](https://www.linkedin.com/in/tiiso-letsapa-664990209).
