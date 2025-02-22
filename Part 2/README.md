# [Part 2] - Exploring the Datasets for Rare Event Analysis

📂 ✨  

### **Different Modalities of Datasets:**
- **Numerical** (including sensor data)
- **Textual**
- **Image**
- **Audio**

### **Levels of Rarity**
- Public rare-event datasets available:
  - **Pulp & Paper Manufacturing Dataset** (Rarity: 0.67%)
  - **Air Pressure System (APS) Failure Dataset** (Rarity: 1.67%)
  - **Bosch Production Line Performance Dataset** (Rarity: 0.58%)
  - **Future Factories Dataset** (Rarity: 1.70%)

### **Mainstream Tasks:**
- Rare event detection and prediction
- Anomaly detection and prediction
- Long-term and short-term forecasting

### **Reference:**
Shyalika, Chathurangi, Ruwan Wickramarachchi, and Amit P. Sheth. "A comprehensive survey on rare event prediction." ACM Computing Surveys 57, no. 3 (2024): 1-39.

---

## **Characteristics of Rare Event Datasets and Associated Challenges**

### **Uncertainty:**
- Limited sample size, high class imbalance, and data sparsity reduce confidence and affect generalization in downstream tasks.

### **Skewed Class Distribution and Lack of Data:**
- Class imbalance makes learning patterns for the minority class difficult due to data scarcity.

### **Temporal Property:**
- Capturing time-dependent patterns is challenging due to imbalance and sparsity, requiring specialized techniques.

### **High Dimensionality:**
- Diverse feature sets (numerical, categorical, textual) increase complexity, requiring feature selection or dimensionality reduction.

### **Class Overlap:**
- Overlapping patterns between rare and common events increase misclassification risks, leading to false negatives.

### **Event Complexity:**
- Rare events involve complex relationships between variables, requiring advanced analytical approaches.

---

## **Factors That Cause Rarity in a Dataset**
- **Natural Occurrences**
- **Sampling Bias**
- **Class Definition**
- **Cost and Measurement Errors**
- **Subjective Decisions**

---

## **Rare Event Datasets Used in This Lab**

### **1. Pulp-and-Paper Manufacturing Dataset**
- **Dataset Source:** ProcessMiner Inc.
- **Industry:** Pulp-and-Paper Manufacturing
- **Total Records:** 18,398
- **Collection Duration:** 30 Days
- **Time Interval/Frequency:** Every 2 Minutes / 0.5 Hz
- **Number of Sensors:** 61 (Continuous, Binary, Categorical)
- **Predictor Variables:** x1 - x61
- **Binary Variable:** x61 (Binary: 0 or 1)
- **Categorical Variable:** x28 (Paper type)
- **Rare Event Count (y=1):** 124 (Sheet Breaks)
- **Majority Class Count (y=0):** 18,274

**Reference:**
Ranjan, Chitta, Mahendranath Reddy, Markku Mustonen, Kamran Paynabar, and Karim Pourak. "Dataset: rare event classification in multivariate time series." arXiv preprint arXiv:1809.10717 (2018).

### **2. Future Factories (FF) Multimodal Dataset**
- **Industry Application:** Rocket Assembly Pipeline
- **Dataset Versions:** Analog and Multimodal
- **Total Records:** 166K
- **Collection Duration:** 30 Hours
- **Sampling Rate:** 1.95 Hz
- **Sensor Types:** Potentiometer, Loadcell, Conveyor Sensors, Robot Angles, Drive Temperatures
- **Multimodal Component:** Synchronized images from two cameras capturing operations
- **Assembly Cycles:** 285 (Complete assembly-disassembly cycles)
- **Cycle States:** 21 distinct cycle states
- **Data Format:** Tabular format extracted from JSON, includes sensor data and image paths
- **Anomaly Types:** Seven (NoNose, NoBody2, NoBody1; NoNose; NoNose, NoBody2; NoBody1; NoBody2, NoBody1; NoBody2; E_STOPPED)

**Dataset Source:** McNair Aerospace Center, University of South Carolina

**Reference:**
Ramy Harik, Fadi El Kalach, Jad Samaha, Devon Clark, Drew Sander, Philip Samaha, Liam Burns, Ibrahim Yousif, Victor Gadow, Teddy Tarekegne, Nitol Saha "Analog and Multi-modal Manufacturing Datasets Acquired on the Future Factories Platform." arXiv preprint arXiv:2401.15544 (2024).



🔙 [Return to the main page](../)
