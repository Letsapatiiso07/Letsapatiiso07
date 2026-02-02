# Tiiso Letsapa
**Data Engineer | AI Engineer | ML Engineer | MLOps Engineer | Cloud Engineer**  
*Building intelligent data systems that bridge cloud infrastructure, machine learning, and engineering innovation*  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/tiiso-letsapa-664990209) [![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/Letsapatiiso07) [![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:Letsapamyron07@gmail.com)

---
## About Me
I'm a **data engineer and machine learning specialist** based in Pretoria, South Africa, with a passion for architecting scalable data pipelines and deploying production-grade machine learning systems. With 3+ years of hands-on experience, I've delivered solutions that process millions of records daily while maintaining 99.5%+ reliability and reducing operational costs by up to 85%.  

**What drives me:** Turning complex data challenges into elegant, automated solutions that create real business value—from fintech risk modeling to aerospace optimization.

### Quick Stats
- **7+ production pipelines** processing 1.2M+ records/hour
- **AWS-certified** cloud architect specializing in serverless architectures
- **90%+ accuracy** ML models in production (including 17% efficiency gains in aerospace optimization)
- **500× speedup** achieved through ML surrogate modeling
- **30-85% cost reduction** across multiple projects
- **99.5% uptime** through robust monitoring and error handling

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
    "ml_ai": ["TensorFlow", "PyTorch", "Scikit-Learn", "XGBoost", "CNNs", "Transfer Learning", "Ensemble Methods"],
    "optimization": ["Genetic Algorithms", "Particle Swarm Optimization", "Gradient-based Methods"],
    "simulation": ["CFD", "Panel Methods", "Physics-based Modeling"],
    "devops": ["Docker", "CI/CD", "GitHub Actions", "Infrastructure as Code"],
    "frontend": ["React", "Streamlit", "TailwindCSS", "Vite", "Plotly"]
}
```

---
## Featured Projects

### ✈️ Airfoil Optimization System
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
- Showcases ability to build **domain-specific AI systems** that solve real engineering problems

**System Architecture:**
```
Flight Specs → PARSEC/CST → CFD Simulation → ML Surrogate (500× faster)
                                                      ↓
Optimized Design ← Analysis ← Genetic Algorithm ← Performance Prediction
```

**Tech Stack:** Python • PyTorch • XGBoost • Scikit-learn • NumPy • SciPy • Matplotlib • Plotly • Streamlit  
**Interactive UI:** Real-time airfoil design with parameter sliders and live performance visualization  
[View Project →](https://github.com/Letsapatiiso07/airfoil-optimization)

---

<img width="800" height="566" alt="image" src="https://github.com/user-attachments/assets/ce8ca65b-9a74-4d51-86e5-db629e13c904" />

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

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/180d29d4-a3c6-487a-9054-7c3b0ccd27fb" />
<img width="550" height="313" alt="image" src="https://github.com/user-attachments/assets/bcafa742-6e43-4823-815c-ea58da1a3d61" />
<img width="850" height="567" alt="image" src="https://github.com/user-attachments/assets/3a89b130-1871-4610-af2a-06c6da3e0f91" />

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
## System Architecture Philosophy
I design cloud-native, serverless-first, and event-driven architectures for maximum scalability and cost efficiency:
```
┌─────────────────────┐ ┌──────────────────────┐ ┌─────────────────────┐
│ 📊 Data Sources │───▶│ 🔄 Ingestion Layer │───▶│ 🏗️ Processing │
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

---
## What Makes Me Tick
**Local meets global:** Combining South African insights with cloud-scale infrastructure  
**Passion-driven projects:** Built an F1 predictor merging hobbies with tech  
**Cross-domain expertise:** From aerospace optimization to fintech risk modeling  
**Serverless advocate:** If it can run without a server, I'm interested  
**Healthcare AI:** Applying ML to medical imaging  
**Fintech & Finance:** Leveraging financial management knowledge with ML for credit risk modeling  
**Engineering + ML:** Bridging physics-based simulation with intelligent optimization  
**Continuous learner:** Exploring real-time streaming and advanced MLOps  
**My goal:** Build data systems so reliable, they become invisible

---
## Let's Connect
I'm always excited to collaborate on data engineering, ML, fintech, aerospace, or cloud projects. Let's talk!  
**Email:** [Letsapamyron07@gmail.com](mailto:Letsapamyron07@gmail.com)  
**LinkedIn:** [linkedin.com/in/tiiso-letsapa-664990209](https://www.linkedin.com/in/tiiso-letsapa-664990209)  
**GitHub:** [github.com/Letsapatiiso07](https://github.com/Letsapatiiso07)

---
*"Building intelligent systems that turn data into decisions—from cloud infrastructure to aerospace innovation"*  
*Based in Pretoria, South Africa 🇿🇦 | Open to remote opportunities worldwide *

My Solution:
Built a complete ML pipeline that:
1️ Parameterizes airfoil geometry using PARSEC method (11 parameters)
2️⃣ Simulates aerodynamic performance with CFD (panel method + boundary layer)
3️⃣ Trains ensemble ML models (Neural Net + XGBoost + Random Forest) achieving R² > 0.98
4️⃣ Optimizes designs using genetic algorithms - 500× faster than pure CFD!

Results:
- 17.4% improvement in L/D ratio vs. NACA 2412
- 10.8% drag reduction
- 4.7% lift increase
- Processing time: 15-30 mins vs. days with traditional methods
- Interactive Streamlit dashboard for real-time design exploration

Technical Stack:
Python • PyTorch • XGBoost • Scikit-learn • NumPy • SciPy • Streamlit • Plotly

Real-World Applications:
UAV and aircraft wing design
Wind turbine blade optimization  
Motorsports aerodynamics
Engineering education & research

This project demonstrates how combining physics-based simulation with machine learning can solve complex engineering problems while dramatically reducing computation time and cost.

The entire system is open source on GitHub - perfect for aerospace engineers, researchers, and ML practitioners interested in domain-specific AI applications!

What engineering challenges do you think could benefit from this ML + physics approach?

#MachineLearning #AerospaceEngineering #DataScience #Python #MLOps #Engineering #AI #CFD #Optimization #CloudComputing

🔗 GitHub: https://github.com/Letsapatiiso07/airfoil-optimization

---

Built with passion for solving real-world engineering problems through intelligent automation

P.S. This adds to my portfolio of domain-specific ML applications - from fintech risk modeling to healthcare AI to aerospace optimization. Always exploring new ways to apply data science to real-world challenges!
