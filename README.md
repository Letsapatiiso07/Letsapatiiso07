## 👋 Hi, I'm Tiiso!

**Data Engineer | Python Automation Specialist | Financial Data Expert**  
Certified in **IT Automation (Google)** and **Data Engineering (DataCamp)** with a diploma in **Financial Management**, I specialize in building data solutions that bridge technical systems and business value.

### 🏆 Certifications
- 🧠 **Google IT Automation with Python Professional Certificate**
- 📊 **DataCamp Certified Data Engineer**
- 💼 **Diploma in Financial Management**

---

## 🏗️ Architecture Overview

```text
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   EventBridge   │───▶│   AWS Lambda    │───▶│   Amazon S3     │
│  (Every 15min)  │    │  Data Ingestion │    │   Raw Storage   │
└─────────────────┘    └─────────────────┘    └─────────────────┘
                                │
                                ▼
                       ┌─────────────────┐    ┌─────────────────┐
                       │   DynamoDB      │    │   CloudWatch    │
                       │  Structured DB  │    │   Monitoring    │
                       └─────────────────┘    └─────────────────┘
```

---

## 📊 Real-Time Data Collection

- **Cities Monitored**: Pretoria, Cape Town, Johannesburg, Durban
- **Collection Frequency**: Every 15 minutes (96 data points/day per city)
- **Data Metrics**: Temperature, Humidity, Pressure, Weather Conditions, Wind Speed

---

## ⚡ Key Features

✅ **Fully Automated ETL Pipeline** – Zero manual intervention  
✅ **Real-Time Processing** – Live data ingestion from OpenWeatherMap  
✅ **Dual Storage Strategy** – Raw JSON (S3) + Structured data (DynamoDB)  
✅ **Error Handling & Logging** – Integrated with CloudWatch  
✅ **Scalable Architecture** – Serverless, event-driven, auto-scaling  
✅ **Cost Optimized** – Runs fully within AWS Free Tier  

---

## 🛠️ Tech Stack

| Component    | Technology             | Purpose                      |
|--------------|------------------------|------------------------------|
| Compute      | AWS Lambda (Python 3.9) | Data processing & ETL        |
| Storage      | Amazon S3              | Raw data lake                |
| Database     | DynamoDB               | Real-time structured queries |
| Scheduler    | EventBridge            | Automated 15-min triggers    |
| Monitoring   | CloudWatch             | Logs & error tracking        |
| API Source   | OpenWeatherMap         | Weather data ingestion       |

---

## 🧪 Sample Output

```json
{
  "city": "Pretoria",
  "temp": 17.44,
  "humidity": 65,
  "pressure": 1013.25,
  "wind_speed": 3.2,
  "weather": "Clear",
  "description": "clear sky",
  "timestamp": "2025-08-17T16:40:41.346533"
}
```

---

## 📁 Project Structure

```
aws-weather-pipeline/
├── lambda_functions/
│   └── weather_ingestion/
│       ├── lambda_function.py
│       └── requirements.txt
├── data_samples/
│   └── sample_s3_data.json
├── deployment/
├── monitoring/
├── architecture/
├── docs/
└── README.md
```

---

## 📈 Related Projects

### 📦 **Inventory Optimization Engine**
> ML-powered system using XGBoost and Prophet  
> 📉 Reduced inventory costs by 30% via EOQ modeling

### 🤖 **Autonomous Crypto Analyst**
> CLI-driven market analyzer with CoinGecko API  
> ⏱️ Reduced reporting time by 85%

### ⚡ **IoT Data Factory**
> Real-time ETL for 1.2M+ sensor readings/hour  
> 📊 Web dashboard with built-in anomaly detection

### 🏦 **Financial Data Accelerator**
> Automated 7 financial workflows using Airflow & Pandas  
> 📅 Month-end close reduced from 3 days to 4 hours

---

## 📫 Let's Build Together

```yaml
name: Tiiso Letsapa
title: Data Engineer | Python Automation Specialist
email: letsapamyron07@gmail.com
location: South Africa
linkedin: https://linkedin.com/in/tiiso-letsapa-664990209
github: https://github.com/Letsapatiiso07
```

### ⚡ Fun Facts
- Automated my first financial model at 19
- Can debug Python while half-asleep 😴🐍
- Believe data pipelines should be as elegant as the insights they deliver

## 📜 License

This project is licensed under the [MIT License](LICENSE).




