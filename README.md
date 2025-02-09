## **📌 Project Description**

### **🔹 Background**
In drilling operations, **Bottom Hole Circulating Temperature (BHCT)** plays a crucial role in **well stability, mud properties, and overall drilling efficiency**. Accurately predicting BHCT is essential for optimizing **drilling fluid design** and **preventing downhole complications**.

### **🔹 Problem Statement**
Traditional methods of estimating BHCT rely on **empirical correlations or simplified models**, which often fail to account for **complex drilling conditions, fluid dynamics, and real-time operational variations**. Additionally, inconsistent data, **outliers, and missing values** further degrade predictive accuracy.

### **🔹 Project Objective**
This project aims to **develop a robust predictive model** for BHCT using **machine learning algorithms** to:
✅ Improve prediction accuracy over conventional models.  
✅ Handle missing and erroneous data effectively.  
✅ Capture both feature interactions and sequential dependencies in drilling data.  

### **🔹 Significance of the Project**
- **Enhances Well Safety** → Better BHCT prediction reduces the risk of **wellbore instability**.
- **Optimizes Mud Design** → Helps engineers adjust **mud rheology** for efficient heat transfer.
- **Improves Decision-Making** → Enables real-time **BHCT monitoring** using AI-driven insights.

---

## **🛠️ Proposed Methodology**
To build a **robust and accurate model**, we will explore a combination of **tree-based boosting models** and **deep learning techniques**:

### **1️⃣ XGBoost & CatBoost (Tree-Based Boosting)**
✅ **XGBoost** → Effective at handling structured data, mitigating overfitting, and **capturing complex feature interactions**.  
✅ **CatBoost** → Excels in handling categorical features, missing values, and **provides stability across noisy datasets**.

### **2️⃣ LSTM (Long Short-Term Memory)**
✅ **LSTM** will be used to capture **sequential dependencies** in drilling operations, ensuring the model learns from **historical trends and dynamic changes**.

### **🔹 Additional Data Processing Steps**
📌 **Missing Data Handling** → Use **MissForest (RandomForest-based imputation)** for filling missing values.  
📌 **Feature Engineering** → Generate **relevant drilling parameters** that influence BHCT.  
📌 **Outlier Detection & Removal** → Identify abnormal values using **Isolation Forest & domain knowledge**.  

---

### **🚀 Expected Outcome**
By integrating **XGBoost, CatBoost, and LSTM**, this project aims to create a **highly accurate and generalizable BHCT prediction model**, ensuring better decision-making in **real-time drilling operations**.
