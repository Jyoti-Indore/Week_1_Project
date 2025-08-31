# 🌍 Climate Risk and Disaster Management Project

This project explores **Climate Risk and Disaster Management** using the **World Risk Index dataset**.  
The dataset provides country-wise disaster risk indicators such as **Exposure, Vulnerability, and Adaptive Capacity**, which together shape the **World Risk Index**.

---

## 📂 Dataset
- **Source:** [World Disaster Risk Index (Kaggle)](https://www.kaggle.com/datasets/tr1gg3rtrash/global-disaster-risk-index-time-series-dataset)  
- **Format:** CSV file  
- **Attributes include:**
  - `Country` – Name of the country  
  - `Year` – Year of data recording  
  - `WorldRiskIndex` – Overall risk index score  
  - `Exposure` – Degree to which a country is exposed to hazards  
  - `Vulnerability` – Susceptibility to damage from hazards  
  - `AdaptiveCapacity` – Capacity to adapt and respond  

---

## ⚙️ Project Workflow
1. **Import Libraries**  
   Load required Python libraries (Pandas, NumPy, etc.).
2. **Load Dataset**  
   Read the dataset into a Pandas DataFrame.
3. **Data Exploration**  
   - `.info()` → Data types and non-null values  
   - `.describe()` → Statistical summary  
   - `.isnull().sum()` → Missing value analysis  

