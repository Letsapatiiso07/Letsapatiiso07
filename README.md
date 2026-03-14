# Tiiso Letsapa
### Data Engineer | AI Engineer | ML Engineer | MLOps Engineer | Cloud Engineer
**Building intelligent data systems that bridge cloud infrastructure, machine learning, and engineering innovation**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tiiso-letsapa-664990209)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Letsapatiiso07)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Letsapamyron07@gmail.com)

---

## About Me

I'm a data engineer and machine learning specialist based in Pretoria, South Africa, with a passion for architecting scalable data pipelines and deploying production-grade machine learning systems. With 4+ years of hands-on experience, I've delivered solutions that process millions of records daily while maintaining 99.5%+ reliability and reducing operational costs by up to 85%.

**What drives me:** Turning complex data challenges into elegant, automated solutions that create real business value — from fintech risk modeling to renewable energy optimization to aerospace engineering.

---

## Quick Stats

| Metric | Value |
|---|---|
| Production pipelines | 7+ processing 1.2M+ records/hour |
| Cloud | AWS-certified serverless architect |
| ML accuracy | 90%+ in production (17% aerospace efficiency gains) |
| Speedup achieved | 500× via ML surrogate modeling |
| Cost reduction | 30–85% across multiple projects |
| Uptime | 99.5% through robust monitoring |
| Production code | 5,900+ lines (renewable energy system alone) |
| Environmental impact | $150M+ potential value from wind optimization |

---

## Latest Certifications & Education

| Certification / Qualification | Provider / Institution | Year |
|---|---|---|
| Diploma in Financial Management | Regent Business School | 2025 |
| Data Engineer Professional | DataCamp | 2025 |
| Associate Data Engineer | DataCamp | 2025 |
| SQL Associate | DataCamp | 2025 |
| Machine Learning Engineer | DataCamp | 2025 |
| AI Engineer For Data Scientists Associate | DataCamp | 2025 |
| IT Automation with Python | Google | 2025 |
| Azure Solutions Architect | Microsoft | 2025 |
| Azure AI Engineer Associate | Microsoft | 2025 |
| Azure Data Scientist Associate | Microsoft | 2025 |
| Fabric Data Engineer Associate | Microsoft | 2026 |

---

## Technical Skills

```python
skills = {
    "languages":        ["Python", "SQL", "TypeScript", "JavaScript", "Bash"],
    "cloud":            ["AWS Lambda", "S3", "DynamoDB", "API Gateway", "Step Functions", "Kinesis"],
    "data_engineering": ["Airflow", "Pandas", "NumPy", "ETL Pipelines", "Real-time Streaming"],
    "ml_ai":            ["TensorFlow", "PyTorch", "Scikit-Learn", "XGBoost", "CNNs",
                         "Transfer Learning", "Ensemble Methods", "Neural Networks", "Random Forest"],
    "optimization":     ["Genetic Algorithms (NSGA-II)", "Particle Swarm Optimization",
                         "Gradient-based Methods", "Multi-objective Optimization"],
    "simulation":       ["CFD", "Panel Methods", "BEM Theory", "Physics-based Modeling",
                         "Structural Analysis", "Fatigue Analysis"],
    "devops":           ["Docker", "CI/CD", "GitHub Actions", "Infrastructure as Code"],
    "frontend":         ["React", "Streamlit", "TailwindCSS", "Vite", "Plotly"],
    "renewable_energy": ["Wind Turbine Design", "AEP Calculation", "Weibull Distributions",
                         "Blade Element Momentum Theory", "IEC Standards"],
    "geospatial":       ["Rasterio", "GeoPandas", "Folium", "NDVI/EVI Analysis",
                         "Sentinel-2 Imagery", "Semantic Segmentation"]
}
```

## Featured Projects

### 🛰️ SA Open-Pit Mining Site Analyzer ⭐ NEW!
**Remote Sensing | Computer Vision | Geospatial AI | Environmental Monitoring**

> A fully local, end-to-end AI system that uses satellite imagery and machine learning to analyze South African open-pit mining sites — detecting mine boundaries, monitoring vegetation loss, and forecasting mineral production. No cloud required. Runs entirely on your machine.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

#### Key Achievements

```python
Impact = {
    "sites_covered":     "5 major SA mine sites (Gold, Platinum, Iron, Copper, Coal)",
    "segmentation":      "U-Net 4-class semantic segmentation (pit / disturbed / vegetation / background)",
    "forecasting":       "LSTM + Prophet — 5-year production trend prediction",
    "environmental":     "NDVI vegetation loss tracking 2015–2024",
    "pipeline":          "4-step automated pipeline: download → features → train → predict",
    "dashboard":         "Interactive Streamlit app with Folium maps + Plotly charts",
    "tracking":          "MLflow experiment tracking (local mode, no cloud)",
    "offline":           "Fully offline after first run — no cloud dependencies"
}
```

#### Mine Sites Covered

| Site | Mineral | Region | Area |
|---|---|---|---|
| Witwatersrand Gold Fields | 🥇 Gold | Gauteng | 400 km² |
| Rustenburg Platinum Belt | 💎 Platinum | North West | 250 km² |
| Sishen Iron Ore Mine | 🔩 Iron | Northern Cape | 180 km² |
| Palabora Copper Mine | 🟠 Copper | Limpopo | 120 km² |
| Grootegeluk Coal Mine | ⚫ Coal | Limpopo | 95 km² |

#### Technical Deep Dive

```python
Pipeline = {
    "imagery": {
        "source":      "Sentinel-2 proxy (4-band: R, G, B, NIR)",
        "resolution":  "256×256 px (~10m ground resolution)",
        "indices":     ["NDVI", "EVI", "BSI (Bare Soil Index)"]
    },
    "segmentation": {
        "model":       "U-Net (encoder-decoder with skip connections)",
        "input":       "4-band satellite tile, 64×64 patches",
        "output":      "4-class pixel mask",
        "loss":        "CrossEntropy + Dice (0.5 weight each)",
        "optimizer":   "Adam + Cosine Annealing LR",
        "device":      "Auto GPU/CPU fallback"
    },
    "forecasting": {
        "lstm":        "2-layer LSTM, hidden=64, autoregressive rollout",
        "prophet":     "Multiplicative seasonality, 1990–2024 history",
        "horizon":     "5-year configurable forecast window",
        "tracking":    "MLflow (local ./mlruns, no cloud)"
    },
    "environmental": {
        "ndvi_trend":  "Linear regression over 2015–2024 annual NDVI",
        "risk_matrix": "Per-site erosion risk scoring across all sites",
        "outputs":     "Vegetation loss %, bare soil increase, trend/yr"
    },
    "dashboard": {
        "tabs":        6,
        "map":         "Folium interactive choropleth",
        "charts":      "Plotly production trends + NDVI time-series",
        "upload":      "Custom GeoTIFF / PNG for live segmentation"
    }
}
```

#### System Architecture

```
┌──────────────────────────────────────────────────────────────┐
│              SENTINEL-2 SATELLITE IMAGERY (4-band)            │
│              R · G · B · NIR  |  256×256 px per site          │
└───────────────────────┬──────────────────────────────────────┘
                        │
                        ▼
┌──────────────────────────────────────────────────────────────┐
│                  FEATURE ENGINEERING                          │
│  NDVI · EVI · BSI  |  Pit metrics  |  Lagged production feats│
└───────────────────────┬──────────────────────────────────────┘
                        │
           ┌────────────┴────────────┐
           ▼                         ▼
┌─────────────────────┐   ┌────────────────────────┐
│   U-NET SEGMENTATION│   │  LSTM + PROPHET FORECAST│
│   4-class pixel mask│   │  5-year production trend│
│   IoU tracked via   │   │  MLflow experiment logs │
│   MLflow            │   │  per-site model weights │
└──────────┬──────────┘   └────────────┬───────────┘
           │                           │
           └────────────┬──────────────┘
                        ▼
┌──────────────────────────────────────────────────────────────┐
│              STREAMLIT INTERACTIVE DASHBOARD                  │
│  Site Map · Imagery · Segmentation · Forecast · NDVI · Upload │
└──────────────────────────────────────────────────────────────┘
```

#### Dashboard Features

| Tab | Content |
|---|---|
| Site Map | Interactive Folium map — all 5 SA mine sites colour-coded by mineral |
| Imagery | RGB composite · NDVI map · pre-computed segmentation side-by-side |
| Segmentation | U-Net overlay with adjustable opacity + land cover pie chart |
| Production | Historical 1990–2024 + LSTM/Prophet 5-year forecast |
| Environment | NDVI degradation trend + vegetation/bare soil charts + risk matrix |
| Upload | Drag-and-drop custom GeoTIFF or PNG for live segmentation |

#### Why This Matters

> South Africa's mining sector contributes ~8% of GDP and employs hundreds of thousands of people across 5 provinces. Remote sensing and ML can help:

- **Monitor environmental impact** — track vegetation loss and erosion around mine sites year over year
- **Detect boundary changes** — automatically map pit expansion using satellite data
- **Forecast production** — anticipate output trends to support supply chain and investment decisions
- **Democratise tools** — open-source alternative to expensive proprietary geospatial software
- **Local relevance** — built specifically for SA conditions, minerals, and mine regions

#### Get Started

```bash
git clone https://github.com/Letsapatiiso07/sa-mining-analyzer
cd sa-mining-analyzer

# One-command setup (Linux/macOS)
bash setup.sh

# Or manual (Windows)
python -m venv venv && venv\Scripts\activate
pip install -r requirements.txt
python scripts/01_download_and_process.py
python scripts/02_features.py
python scripts/03_train.py
python scripts/04_predict.py

# Launch dashboard
streamlit run app.py
```

**Tech Stack:**
Python · PyTorch · Rasterio · GeoPandas · Folium · Streamlit · Plotly · Prophet · MLflow · Scikit-learn · NumPy

**[View Project →](https://github.com/Letsapatiiso07/mining_analyzer)**

---

### Wind Turbine Blade Optimizer ⭐
**Renewable Energy | Machine Learning | Optimization | Sustainability**

Production-ready ML system optimizing wind turbine blade designs for 5–15% energy production improvements — accelerating the global transition to clean energy.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)]()

```python
Impact = {
    "aep_improvement":    "+5-15% over NREL 5MW baseline",
    "computational_speedup": "500× (0.001s vs 0.5s per evaluation)",
    "ml_accuracy":        "R² > 0.95 (ensemble: NN + XGBoost + RF)",
    "production_code":    "5,900+ lines, fully documented",
    "economic_value":     "$150M+ for 100-turbine wind farm (20-year)",
    "environmental":      "75,000 tons CO₂ offset/year potential"
}
```

**Real-World Impact (100-Turbine Wind Farm):**

| Metric | Value |
|---|---|
| Additional Revenue | $7.5M+/year (@$50/MWh) |
| Extra Clean Energy | 150,000 MWh annually |
| CO₂ Offset | 75,000 tons/year |
| 20-Year Value | $150M+ |
| LCOE Reduction | 5–10% |

```python
Pipeline = {
    "parameterization": {
        "method":      "B-spline interpolation",
        "parameters":  15,
        "constraints": "Monotonic chord, min 0.1m, structural feasibility"
    },
    "aerodynamics": {
        "solver":      "BEM (Blade Element Momentum) Theory",
        "corrections": ["Prandtl tip loss", "Glauert high-induction"],
        "speed":       "~0.5s per full power curve"
    },
    "ml_surrogate": {
        "architecture": "Ensemble (NN [128,256,128] + XGBoost + RF)",
        "accuracy":     "R² > 0.95, MAPE < 5%",
        "speedup":      "500× faster than direct BEM"
    },
    "optimization": {
        "algorithms":  ["NSGA-II (GA)", "PSO", "Gradient methods"],
        "population":  100,
        "generations": "300-500",
        "runtime":     "~30 minutes with surrogate"
    }
}
```

```
┌──────────────────────────────────────────────────────────────┐
│           Wind Distribution (Weibull) + Site Data             │
└────────────────────┬─────────────────────────────────────────┘
                     ▼
┌──────────────────────────────────────────────────────────────┐
│              BLADE PARAMETERIZATION (15 params)               │
│  Chord Distribution → Twist Distribution → Airfoil Family     │
└────────────────────┬─────────────────────────────────────────┘
                     ▼
┌──────────────────────────────────────────────────────────────┐
│                  PHYSICS SIMULATION                           │
│  BEM Aerodynamics → Structural Analysis → Fatigue → AEP       │
└────────────────────┬─────────────────────────────────────────┘
                     ▼
┌──────────────────────────────────────────────────────────────┐
│         ML SURROGATE TRAINING (500x SPEEDUP)                  │
│  NN + XGBoost + RF Ensemble  |  R2 > 0.95                    │
└────────────────────┬─────────────────────────────────────────┘
                     ▼
┌──────────────────────────────────────────────────────────────┐
│                   NSGA-II OPTIMIZATION                        │
│  Pop=100, Gen=300-500  |  ~30 minutes runtime                │
└────────────────────┬─────────────────────────────────────────┘
                     ▼
┌──────────────────────────────────────────────────────────────┐
│           OPTIMIZED BLADE DESIGN [DONE]                       │
│    5-15% AEP Improvement | Structurally Feasible             │
└──────────────────────────────────────────────────────────────┘
```

**Tech Stack:** Python · PyTorch · XGBoost · Scikit-learn · SciPy · NumPy · PyMOO · Streamlit · Plotly

### Airfoil Optimization System
**Aerospace Engineering | Machine Learning | CFD | Genetic Algorithms**

End-to-end ML system that automatically designs high-performance airfoils, achieving 10–25% efficiency improvements over baseline NACA designs.

```python
Pipeline = {
    "parameterization": "PARSEC (11 parameters) + CST methods",
    "simulation":       "Panel method + boundary layer corrections",
    "ml_models":        "Ensemble (Neural Net + XGBoost + Random Forest)",
    "optimization":     "GA (population=50, 200 iterations)",
    "speedup":          "500x faster than pure CFD",
    "applications":     ["Aircraft design", "Wind turbines", "Motorsports"]
}

Results = {
    "Max L/D":        48.32,
    "Drag reduction": "-10.8%",
    "Lift increase":  "+4.7%",
    "Processing":     "15-30 mins for full optimization"
}
```

**Tech Stack:** Python · PyTorch · XGBoost · Scikit-learn · NumPy · SciPy · Streamlit

### Credit Risk Assessment Dashboard
**Fintech | Machine Learning | Risk Modeling | XGBoost**

End-to-end ML system for predicting loan default risk using borrower financial and demographic data.

```python
Results = {
    "AUC_ROC":         0.945,
    "top_features":    ["Loan grade", "Interest rate", "Debt-to-income", "Home ownership"],
    "models_compared": ["XGBoost (winner)", "Logistic Regression", "KNN"],
    "pipeline":        "Production-ready with preprocessing and evaluation metrics"
}
```

**Tech Stack:** Python · Pandas · Scikit-learn · XGBoost · Matplotlib · Seaborn

### Medical Image Analysis with Deep Learning
**Healthcare AI | Computer Vision | Transfer Learning**

Production-ready medical imaging classification system leveraging CNNs and transfer learning for diagnostic assistance.

**Key Features:**
- Multiple architectures: Custom CNN, VGG16, ResNet50, InceptionV3
- Grad-CAM visualization for model interpretability
- Synthetic medical image generation (X-Ray, Brain MRI)
- Real-time prediction with confidence scores

**Tech Stack:** TensorFlow · Keras · OpenCV · Scikit-learn · Matplotlib

### F1 Race Winner Prediction System
**Machine Learning | Sports Analytics | Feature Engineering**

End-to-end ML system predicting Formula 1 race outcomes with 90% accuracy.

| Metric | Result |
|---|---|
| Race winner accuracy | 90% |
| Podium accuracy | 95%+ |

**Tech Stack:** Python · XGBoost · FastF1 API · Pandas · Scikit-learn

### DataOps Studio
**Interactive Dashboard | Modern UI | Real-time Monitoring**

Modern interactive dashboard showcasing Data Engineering & MLOps capabilities with dark mode, responsive design, and automated CI/CD.

**Tech Stack:** React · TypeScript · TailwindCSS · Recharts · Vite · GitHub Actions

## Other Production Systems

| Project | Tech Stack | Impact |
|---|---|---|
| Weather Analytics Pipeline | AWS Lambda, S3, DynamoDB | 99.5% uptime, <$0.10/month |
| Inventory Optimization Engine | Python, XGBoost, Scikit-Learn | 92% accuracy, 30% cost reduction |
| Cryptocurrency ETL | Python, Airflow, REST APIs | 85% time savings |
| IoT Processing System | Python, SQLite, JavaScript | 1.2M+ records/hour |
| Financial Automation | Airflow, Pandas, PostgreSQL | 3 days → 4 hours |

## Engineering + Sustainability Portfolio

My work demonstrates a unique combination:

| Domain | Project | Impact |
|---|---|---|
| Renewable Energy | Wind Turbine Optimizer | $150M+ value potential |
| Aerospace | Airfoil Design System | 17.4% efficiency gains |
| Fintech | Credit Risk Model | 0.945 AUC-ROC |
| Healthcare | Medical Imaging AI | Transfer learning, Grad-CAM |
| Mining & Environment | SA Mining Site Analyzer | NDVI monitoring, U-Net segmentation |
| Sports Analytics | F1 Predictor | 90% race accuracy |

**Common thread:** Physics-based simulation + Machine learning = Real-world impact

## System Architecture Philosophy

I design cloud-native, serverless-first, and event-driven architectures for maximum scalability and cost efficiency:

```
┌─────────────────────┐   ┌──────────────────────┐   ┌─────────────────────┐
│    Data Sources     │──▶│   Ingestion Layer     │──▶│     Processing      │
│                     │   │                      │   │                     │
│ REST/GraphQL APIs   │   │ AWS API Gateway       │   │ AWS Lambda          │
│ IoT Sensors/MQTT    │   │ Amazon Kinesis        │   │ Step Functions      │
│ Database CDC        │   │ AWS EventBridge       │   │ Glue ETL Jobs       │
│ File Uploads        │   │ SQS/SNS Queues        │   │ Error Handling      │
│ Streaming Data      │   │ Scheduled Triggers    │   │ Dead Letter Queue   │
└─────────────────────┘   └──────────────────────┘   └─────────────────────┘
```

## Performance Metrics

| Metric | Target | Achieved |
|---|---|---|
| Pipeline Uptime | 99.9% | 99.5% |
| Processing Latency | <100ms | <200ms |
| Cost per TB | <$10 | $15 |
| Error Rate | <0.1% | <0.5% |
| ML Speedup | 100× | 500× |
| Production Code | Professional | 5,900+ lines |

## What Makes Me Tick

- **Local meets global** — Combining South African insights with cloud-scale infrastructure
- **Passion-driven projects** — Built an F1 predictor merging hobbies with tech
- **Cross-domain expertise** — From aerospace to renewable energy to fintech to geospatial AI
- **Sustainability champion** — Using ML to accelerate clean energy transition and monitor environmental impact
- **Serverless advocate** — If it can run without a server, I'm interested
- **Healthcare AI** — Applying ML to medical imaging
- **Mining & Environment** — Using satellite imagery and AI to monitor South Africa's mining landscape
- **Engineering + ML** — Bridging physics-based simulation with intelligent optimization
- **Open source contributor** — Sharing renewable energy and geospatial tools with the research community
- **Continuous learner** — Always exploring new ways to apply AI to real-world challenges

> *My goal: Build data systems so reliable, they become invisible — while making the world greener*

## Let's Connect

I'm always excited to collaborate on data engineering, ML, renewable energy, aerospace, fintech, geospatial AI, or cloud projects.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tiiso_Letsapa-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/tiiso-letsapa-664990209)
[![GitHub](https://img.shields.io/badge/GitHub-Letsapatiiso07-100000?style=for-the-badge&logo=github)](https://github.com/Letsapatiiso07)
[![Email](https://img.shields.io/badge/Email-Letsapamyron07@gmail.com-D14836?style=for-the-badge&logo=gmail)](mailto:Letsapamyron07@gmail.com)

Based in Pretoria, South Africa 🇿🇦 | Open to remote and hybrid opportunities worldwide

> *"Building intelligent systems that turn data into decisions — from cloud infrastructure to renewable energy innovation to satellite-based environmental monitoring"*

**P.S.** Latest achievements:
- **SA Mining Site Analyzer** — U-Net segmentation + LSTM forecasting on real SA mine sites, fully local, open-source
- **Wind Turbine Blade Optimizer** — 5,900 lines of production code, 500× speedup, $150M+ potential value

*Built with passion for solving real-world challenges through intelligent automation and sustainable innovation.*
