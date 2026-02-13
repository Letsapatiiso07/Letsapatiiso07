# Tiiso Letsapa
**Data Engineer | AI Engineer | ML Engineer | MLOps Engineer | Cloud Engineer**  
*Building intelligent data systems that bridge cloud infrastructure, machine learning, and engineering innovation*  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/tiiso-letsapa-664990209) [![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/Letsapatiiso07) [![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:Letsapamyron07@gmail.com)

---
## About Me
I'm a **data engineer and machine learning specialist** based in Pretoria, South Africa, with a passion for architecting scalable data pipelines and deploying production-grade machine learning systems. With 3+ years of hands-on experience, I've delivered solutions that process millions of records daily while maintaining 99.5%+ reliability and reducing operational costs by up to 85%.  

**What drives me:** Turning complex data challenges into elegant, automated solutions that create real business value—from fintech risk modeling to renewable energy optimization to aerospace engineering.

### Quick Stats
- **7+ production pipelines** processing 1.2M+ records/hour
- **AWS-certified** cloud architect specializing in serverless architectures
- **90%+ accuracy** ML models in production (including 17% efficiency gains in aerospace optimization)
- **500× speedup** achieved through ML surrogate modeling (aerospace & renewable energy)
- **30-85% cost reduction** across multiple projects
- **99.5% uptime** through robust monitoring and error handling
- **5,900+ lines** of production code in renewable energy optimization
- **$150M+ potential value** from wind turbine optimization for 100-turbine farms

---
## Latest Certifications & Education
| Certification / Qualification | Provider / Institution | Year |
|-------------------------------|------------------------|------|
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

---
## Technical Skills
```python
skills = {
    "languages": ["Python", "SQL", "TypeScript", "JavaScript", "Bash"],
    "cloud": ["AWS Lambda", "S3", "DynamoDB", "API Gateway", "Step Functions", "Kinesis"],
    "data_engineering": ["Airflow", "Pandas", "NumPy", "ETL Pipelines", "Real-time Streaming"],
    "ml_ai": ["TensorFlow", "PyTorch", "Scikit-Learn", "XGBoost", "CNNs", "Transfer Learning", 
              "Ensemble Methods", "Neural Networks", "Random Forest"],
    "optimization": ["Genetic Algorithms (NSGA-II)", "Particle Swarm Optimization", 
                     "Gradient-based Methods", "Multi-objective Optimization"],
    "simulation": ["CFD", "Panel Methods", "BEM Theory", "Physics-based Modeling", 
                   "Structural Analysis", "Fatigue Analysis"],
    "devops": ["Docker", "CI/CD", "GitHub Actions", "Infrastructure as Code"],
    "frontend": ["React", "Streamlit", "TailwindCSS", "Vite", "Plotly"],
    "renewable_energy": ["Wind Turbine Design", "AEP Calculation", "Weibull Distributions",
                         "Blade Element Momentum Theory", "IEC Standards"]
}
```

---
## Featured Projects

### Wind Turbine Blade Optimizer ⭐ **NEW!**
*Renewable Energy | Machine Learning | Optimization | Sustainability*  
**Production-ready ML system optimizing wind turbine blade designs for 5-15% energy production improvements**—accelerating the global transition to clean energy.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-red.svg)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<!-- Add your dashboard screenshot here -->
<!-- ![Wind Turbine Dashboard](path/to/dashboard-screenshot.png) -->

**Key Achievements:**
```python
Impact = {
    "aep_improvement": "+5-15% over NREL 5MW baseline",
    "computational_speedup": "500× (0.001s vs 0.5s per evaluation)",
    "ml_accuracy": "R² > 0.95 (ensemble: NN + XGBoost + RF)",
    "production_code": "5,900+ lines, fully documented",
    "economic_value": "$150M+ for 100-turbine wind farm (20-year)",
    "environmental": "75,000 tons CO₂ offset/year potential"
}
```

**Real-World Impact (100-Turbine Wind Farm):**
- **Additional Revenue:** $7.5M+ per year (@$50/MWh)
- **Extra Clean Energy:** 150,000 MWh annually
- **CO₂ Offset:** 75,000 tons/year
- **20-Year Value:** $150M+
- **LCOE Reduction:** 5-10%

**Technical Deep Dive:**
```python
# Complete System Architecture
Pipeline = {
    "parameterization": {
        "method": "B-spline interpolation",
        "parameters": 15,  # 6 chord + 6 twist + 3 airfoil families
        "constraints": "Monotonic chord, min 0.1m, structural feasibility"
    },
    "aerodynamics": {
        "solver": "BEM (Blade Element Momentum) Theory",
        "corrections": ["Prandtl tip loss", "Glauert high-induction"],
        "outputs": "Power, thrust, torque, Cp, loads",
        "speed": "~0.5s per full power curve"
    },
    "structural": {
        "model": "1D Euler-Bernoulli beam",
        "analysis": ["Deflection", "Stress", "Mass", "Fatigue"],
        "constraints": ["Tip deflection < 5%", "Stress ratio < 1.0", "Fatigue D < 1.0"],
        "materials": "Composite (E=40 GPa, ρ=1800 kg/m³)"
    },
    "ml_surrogate": {
        "architecture": "Ensemble (NN [128,256,128] + XGBoost + RF)",
        "training_data": "10k-100k Latin Hypercube samples",
        "features": 15,  # geometry parameters
        "targets": ["AEP", "Cp", "mass", "deflection", "stress"],
        "accuracy": "R² > 0.95, MAPE < 5%",
        "speedup": "500× faster than direct BEM"
    },
    "optimization": {
        "algorithms": ["NSGA-II (GA)", "PSO", "Gradient methods"],
        "population": 100,
        "generations": "300-500",
        "objectives": "Maximize AEP, minimize mass",
        "runtime": "~30 minutes with surrogate"
    }
}

# Performance Results
Results = {
    "baseline": {
        "design": "NREL 5MW Reference Turbine",
        "aep": "14,850 MWh/year",
        "capacity_factor": "33.8%",
        "blade_mass": "17,740 kg",
        "max_cp": 0.465
    },
    "optimized": {
        "aep": "16,320 MWh/year (+9.9%)",
        "capacity_factor": "37.2% (+10.1%)",
        "blade_mass": "16,890 kg (-4.8%)",
        "max_cp": "0.487 (+4.7%)"
    }
}
```

**System Architecture:**
```
┌─────────────────────────────────────────────────────────────┐
│          Wind Distribution (Weibull) + Site Data             │
│                     Mean Speed: 8.5 m/s                      │
└────────────────────┬────────────────────────────────────────┘
                     │
                     ▼
┌─────────────────────────────────────────────────────────────┐
│               BLADE PARAMETERIZATION (15 params)             │
│  Chord Distribution → Twist Distribution → Airfoil Family    │
│      (6 B-spline)         (6 B-spline)        (3 types)     │
└────────────────────┬────────────────────────────────────────┘
                     │
                     ▼
┌─────────────────────────────────────────────────────────────┐
│                  PHYSICS SIMULATION                          │
│  BEM Aerodynamics → Structural Analysis → Fatigue → AEP      │
│  (Power, Cp, Loads) (Deflection, Stress)  (D<1.0)  (MWh/yr) │
│                    ~0.5s per evaluation                      │
└────────────────────┬────────────────────────────────────────┘
                     │
                     ▼
┌─────────────────────────────────────────────────────────────┐
│         ML SURROGATE TRAINING (500× SPEEDUP!)                │
│  Database: 10k-100k samples (Latin Hypercube Sampling)       │
│  Models: NN + XGBoost + RF → Ensemble (R² > 0.95)           │
│  Prediction: ~0.001s (500× faster!)                          │
└────────────────────┬────────────────────────────────────────┘
                     │
                     ▼
┌─────────────────────────────────────────────────────────────┐
│                   OPTIMIZATION                               │
│  NSGA-II GA: Pop=100, Gen=300-500, Multi-objective           │
│  Constraints: Fatigue D<1, Deflection<5%, Stress OK          │
│  Runtime: ~30 minutes                                        │
└────────────────────┬────────────────────────────────────────┘
                     │
                     ▼
┌─────────────────────────────────────────────────────────────┐
│              OPTIMIZED BLADE DESIGN ✓                        │
│  5-15% AEP Improvement | Structurally Feasible | Ready!      │
└─────────────────────────────────────────────────────────────┘
```

**Why This Matters:**
- **Climate Impact:** Direct contribution to renewable energy transition
- **Innovation:** Demonstrates physics + ML integration for sustainability
- **Industry-Ready:** Production-quality code (5,900 lines), comprehensive testing
- **Open Source:** MIT license, contributing to research community
- **Educational:** Complete pipeline from parameterization to deployment
- **Economic Value:** Millions in additional revenue for wind farms

**Key Features:**
- Interactive Streamlit dashboard (no-code interface for engineers)
- Complete CLI pipeline for automation
- Comprehensive documentation (README, API docs, troubleshooting)
- Multi-platform support (Windows, Linux, macOS)
- Deployable demo (Streamlit Cloud ready)
- Uncertainty quantification via ensemble variance
- Real-world validation against NREL 5MW baseline

**Tech Stack:**  
Python • PyTorch • XGBoost • Scikit-learn • SciPy • NumPy • PyMOO • Streamlit • Plotly • h5py • Pandas

**Interfaces:**  
Interactive Streamlit Dashboard | CLI Pipeline | Python API

[View Project →](https://github.com/Letsapatiiso07/wind-turbine-optimizer) | [Live Demo →](#) | [Read Docs →](#)

---

### Airfoil Optimization System
*Aerospace Engineering | Machine Learning | CFD | Genetic Algorithms*  
End-to-end ML system that automatically designs high-performance airfoils, achieving **10-25% efficiency improvements** over baseline NACA designs through intelligent optimization.

**Key Features & Results:**
- **17.4% improvement** in L/D ratio vs. NACA 2412 baseline
- **500× speedup** over traditional CFD-only approaches (0.001s vs 0.5s per evaluation)
- **R² > 0.98** ML model accuracy for performance prediction
- **Multi-algorithm optimization:** Genetic Algorithm, PSO, gradient-based methods
- Real-time interactive dashboard for airfoil design and analysis

**Technical Highlights:**
```python
# System Architecture:
Pipeline = {
    "parameterization": "PARSEC (11 parameters) + CST methods",
    "simulation": "Panel method + boundary layer corrections",
    "ml_models": "Ensemble (Neural Net + XGBoost + Random Forest)",
    "optimization": "GA (population=50, 200 iterations)",
    "speedup": "500× faster than pure CFD",
    "applications": ["Aircraft design", "Wind turbines", "Motorsports"]
}

# Performance Metrics:
Results = {
    "Max L/D": 48.32,        # vs 41.15 baseline (+17.4%)
    "Drag reduction": -10.8%, 
    "Lift increase": +4.7%,
    "Processing time": "15-30 mins for full optimization"
}
```

**Why It Matters:**
- Demonstrates integration of **physics-based simulation** with **ML optimization**
- Combines **aerospace engineering** principles with modern **data science** techniques
- **Production-ready pipeline:** Database generation → ML training → Optimization → Analysis
- **Practical applications:** UAV design, wind energy, race car aerodynamics

**System Architecture:**
```
Flight Specs → PARSEC/CST → CFD Simulation → ML Surrogate (500× faster)
                                                      ↓
Optimized Design ← Analysis ← Genetic Algorithm ← Performance Prediction
```

**Tech Stack:** Python • PyTorch • XGBoost • Scikit-learn • NumPy • SciPy • Matplotlib • Plotly • Streamlit  
[View Project →](https://github.com/Letsapatiiso07/airfoil-optimization)

---

<img width="800" height="566" alt="Credit Risk Assessment Dashboard" src="https://github.com/user-attachments/assets/ce8ca65b-9a74-4d51-86e5-db629e13c904" />

### Credit Risk Assessment Model
*Fintech | Machine Learning | Risk Modeling | XGBoost*  
End-to-end machine learning system for predicting loan default risk using borrower financial and demographic data.  

**Key Features & Results:**
- **AUC-ROC: 0.945** (excellent predictive performance)
- Comprehensive EDA, outlier handling, and feature engineering (e.g., debt-to-income ratio)
- Model comparison: XGBoost outperformed Logistic Regression and KNN
- Interpretable insights via feature importance and visualizations
- Production-ready pipeline with preprocessing and evaluation metrics

**Technical Highlights:**
```python
# Top predictive features identified:
- Loan grade & interest rate (highest risk drivers)
- Debt-to-income ratio (engineered feature)
- Home ownership status (renters higher risk)
- Loan amount and percent income
```
**Why It Matters:**
- Demonstrates real-world fintech application of ML for credit scoring
- Handles class imbalance and provides actionable risk insights
- Strong addition to financial domain expertise (complements Diploma in Financial Management)

**Tech Stack:** Python • Pandas • Scikit-learn • XGBoost • Matplotlib • Seaborn  
[View Project →](https://github.com/Letsapatiiso07/Credit-Risk-Assessment)

---

<img width="1280" height="720" alt="Medical Image Analysis" src="https://github.com/user-attachments/assets/180d29d4-a3c6-487a-9054-7c3b0ccd27fb" />
<img width="550" height="313" alt="Model Training" src="https://github.com/user-attachments/assets/bcafa742-6e43-4823-815c-ea58da1a3d61" />
<img width="850" height="567" alt="Grad-CAM Visualization" src="https://github.com/user-attachments/assets/3a89b130-1871-4610-af2a-06c6da3e0f91" />

### Medical Image Analysis with Deep Learning
*Healthcare AI | Computer Vision | Transfer Learning*  
A production-ready medical imaging classification system leveraging CNNs and transfer learning for diagnostic assistance.  

**Key Features:**
- Multiple architectures: Custom CNN, VGG16, ResNet50, InceptionV3
- Synthetic medical image generation (X-Ray, Brain MRI)
- Grad-CAM visualization for model interpretability
- Complete training pipeline with data augmentation
- Real-time prediction with confidence scores  

**Tech Stack:** TensorFlow • Keras • OpenCV • Scikit-learn • Matplotlib • Seaborn  
[View Project →](https://github.com/Letsapatiiso07/medical-image-analysis)

---

### F1 Race Winner Prediction System
*Machine Learning | Sports Analytics | Feature Engineering*  
End-to-end ML system predicting Formula 1 race outcomes with 90% accuracy.  

**Results:**
- **90% accuracy** on race winner predictions
- **95%+ accuracy** on podium predictions  

**Tech Stack:** Python • XGBoost • FastF1 API • Pandas • Scikit-learn • Matplotlib  

---

### DataOps Studio
*Interactive Dashboard | Modern UI | Real-time Monitoring*  
A modern, interactive dashboard showcasing Data Engineering & MLOps capabilities.  

**Features:**
- Interactive data visualizations
- Dark mode with responsive design
- Automated CI/CD  

**Tech Stack:** React • TypeScript • TailwindCSS • Recharts • Vite • GitHub Actions

---

### Other Production Systems
| Project | Tech Stack | Impact |
|---------|-----------|--------|
| **Weather Analytics Pipeline** | AWS Lambda, S3, DynamoDB | 99.5% uptime, <$0.10/month |
| **Inventory Optimization Engine** | Python, XGBoost, Scikit-Learn | 92% accuracy, 30% cost reduction |
| **Cryptocurrency ETL** | Python, Airflow, REST APIs | 85% time savings |
| **IoT Processing System** | Python, SQLite, JavaScript | 1.2M+ records/hour |
| **Financial Automation** | Airflow, Pandas, PostgreSQL | 3 days → 4 hours |

---
## Engineering + Sustainability Portfolio

My work demonstrates a unique combination:
- **Renewable Energy:** Wind turbine optimization ($150M+ value potential)
- **Aerospace:** Airfoil design (17.4% efficiency gains)
- **Fintech:** Credit risk modeling (0.945 AUC-ROC)
- **Healthcare:** Medical imaging AI
- **Green Tech:** Supporting global clean energy transition through ML

**Common thread:** Physics-based simulation + Machine learning = Real-world impact

---
## System Architecture Philosophy
I design cloud-native, serverless-first, and event-driven architectures for maximum scalability and cost efficiency:
```
┌─────────────────────┐ ┌──────────────────────┐ ┌─────────────────────┐
│ Data Sources │───▶│ Ingestion Layer │───▶│ Processing │
│                     │   │                      │   │                     │
│ • REST/GraphQL APIs │   │ • AWS API Gateway    │   │ • AWS Lambda        │
│ • IoT Sensors/MQTT  │   │ • Amazon Kinesis     │   │ • Step Functions    │
│ • Database CDC      │   │ • AWS EventBridge    │   │ • Glue ETL Jobs     │
│ • File Uploads      │   │ • SQS/SNS Queues     │   │ • Error Handling    │
│ • Streaming Data    │   │ • Scheduled Triggers │   │ • Dead Letter Queue │
└─────────────────────┘ └──────────────────────┘ └─────────────────────┘
```

---
## Performance Metrics
| Metric | Target | Achieved |
|--------|--------|----------|
| Pipeline Uptime | 99.9% | 99.5% |
| Processing Latency | <100ms | <200ms |
| Cost per TB | <$10 | $15 |
| Error Rate | <0.1% | <0.5% |
| ML Speedup | 100× | 500× |
| Production Code Quality | Professional | 5,900+ lines |

---
## What Makes Me Tick
**Local meets global:** Combining South African insights with cloud-scale infrastructure  
**Passion-driven projects:** Built an F1 predictor merging hobbies with tech  
**Cross-domain expertise:** From aerospace to renewable energy to fintech risk modeling  
**Sustainability champion:** Using ML to accelerate clean energy transition  
**Serverless advocate:** If it can run without a server, I'm interested  
**Healthcare AI:** Applying ML to medical imaging  
**Fintech & Finance:** Leveraging financial management knowledge with ML for credit risk  
**Engineering + ML:** Bridging physics-based simulation with intelligent optimization  
**Open source contributor:** Sharing renewable energy tools with the research community  
**Continuous learner:** Always exploring new ways to apply AI to real-world challenges  
**My goal:** Build data systems so reliable, they become invisible—while making the world greener

---
## Let's Connect
I'm always excited to collaborate on data engineering, ML, renewable energy, aerospace, fintech, or cloud projects. Let's talk!  
**Email:** [Letsapamyron07@gmail.com](mailto:Letsapamyron07@gmail.com)  
**LinkedIn:** [linkedin.com/in/tiiso-letsapa-664990209](https://www.linkedin.com/in/tiiso-letsapa-664990209)  
**GitHub:** [github.com/Letsapatiiso07](https://github.com/Letsapatiiso07)

---
*"Building intelligent systems that turn data into decisions—from cloud infrastructure to renewable energy innovation"*  
*Based in Pretoria, South Africa 🇿🇦 | Open to remote opportunities worldwide | Accelerating the clean energy transition through ML*

---

Built with passion for solving real-world challenges through intelligent automation and sustainable innovation.

*P.S. My latest achievement: Wind Turbine Blade Optimizer—5,900 lines of production code, 500× speedup, $150M+ potential value. Demonstrating how ML can accelerate the renewable energy transition!
