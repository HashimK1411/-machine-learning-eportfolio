# All artefacts demonstrating development over the duration of the module
 

---

## Unit 1: Introduction to Machine Learning  
**Activity Type:** Collaborative Discussion  
**Theme:** The 4ᵗʰ Industrial Revolution  

### Summary of Activity  
I explored how rapid technological advancement, while transformative, introduces critical cybersecurity and governance concerns. Using the **2021 T-Mobile data breach** as a case study, I showed how AI, cloud computing, and big-data interconnectivity can create serious vulnerabilities when cybersecurity is not embedded into digital infrastructure.

### Key Concepts and Insights  
- **Complex Systems & Vulnerabilities**  
- **Skills Gaps in Industry 4.0**  
- **The Shift to Industry 5.0**

### Critical Reflection  
This activity bridged theory and practice. I learned that AI-driven digital transformation must be paired with ethical and legal safeguards. Machine-learning professionals need to design systems with integrity, security and user trust at their core, supported by proactive risk assessment.

---

## Unit 2: Industry 4.0 → 5.0  
**Activity Type:** Collaborative Discussion – Peer Responses  

### Summary of Activity  
Building on Unit 1, I engaged with peers on the transition from **Industry 4.0 to 5.0**. Discussions centred on how Industry 5.0 embeds *ethical, resilient, human-centric* values into technological adoption.

### Critical Reflection  
The change is more than technological—it is a **mind-set shift**, embedding fairness, adaptability, and resilience into digital architectures. These principles now inform my technical problem-solving and stakeholder responsibilities.

---

## Unit 3: Correlation & Regression  
**Theme:** Understanding Linear and Non-linear Relationships in Data  

### Artefacts & Modifications  

| Programme | Technique | Key Modification | Outcome |
|-----------|-----------|------------------|---------|
| **1** | Pearson Correlation (random data) | Added noise, reduced dependency | *r* dropped **0.888 → 0.098** |
| **2** | Simple Linear Regression (noisy data) | Added noise to *y* (`np.random.randint`) | *r* dropped **-0.759 → -0.302**; prediction at *x = 10* changed to **90.45** |
| **3** | Multiple Linear Regression | CSV with `weight`, `volume`, `CO₂` | see coefficients table below |
| **4** | Polynomial Regression | Added noise to *y* | R² **0.94 → 0.76**; prediction at *x = 17* **88.87 → 81.18** |

**Programme 3 Coefficients**

| Feature | Coefficient |
|---------|-------------|
| Weight  | **0.00755** |
| Volume  | **0.00781** |

*Example prediction:* 2300 kg & 1300 cm³ → **≈ 107.21 g CO₂**. Raising weight to 3300 kg → **≈ 114.76 g CO₂**.

### Reflection  
Hands-on coding revealed how noise, overfitting, and model sensitivity influence correlation and regression. These insights prepare me for robust AI modelling in diverse scenarios.

---

## Unit 4: Clustering & Similarity  
Unsupervised learning techniques for pattern recognition and segmentation.

### Artefact 1 – **K-Means Clustering**  
A live animation demonstrated centroid shifts and cluster formation, clarifying **intra-cluster similarity** and **inter-cluster distance**.

### Artefact 2 – **Jaccard Similarity**

| Pair           | Jaccard |
|----------------|---------|
| Jack & Mary    | **0.33** |
| Jack & Jim     | **0.67** |
| Jim & Mary     | **0.75** |

### Reflection  
Visual and mathematical artefacts showed how to segment unlabeled data and compare binary features—skills vital for profiling, anomaly detection, and recommender systems.

---

## Units 5 & 6: Group Project – Predicting Airbnb Prices  
**Theme:** Collaborative ML Project on Real-World Data  

### Group Collaboration Overview  
- Weekly meetings (Units 1 → 6)  
- **Business Question:** What factors most influence Airbnb pricing? (e.g., location, beds, reviews)

### Unit 5 Artefact – **EDA & Initial Model**  
- Data cleaning and exploratory analysis  
- Baseline linear regression  
- Learned the impact of feature selection and shared responsibilities.

### Unit 6 Artefact – **Final Report**  
- Model refinements and alternative configurations  
- Comprehensive paper: business context, pipeline, results, reflections.

### Reflection  
The project strengthened my technical and interpersonal skills—highlighting communication, mutual support, and adaptability when handling messy real-world data.

---

## Unit 7: Introduction to Artificial Neural Networks  

### Part 1 – **Simple Perceptron**  
NumPy simulation of weighted sums + step activation.

### Part 2 – **Perceptron Learning: AND Gate**  
Implemented weight-update loop until perfect classification.

### Part 3 – **Multi-Layer Perceptron (MLP)**  
Showed how hidden layers and back-propagation extend learning capacity.

### Reflection  
Guided activities reinforced core ANN concepts—inputs, weights, activation, and the transition from single-layer to layered models.

---

## Units 8–10: Forum Reflection – AI-Assisted Writing  

### Summary of Activity  
Explored AI tools (ChatGPT, GPT-3) and their **benefits vs. risks**.  
Key literature: Hutson (2021); Harati (2024); Carobene et al. (2023).

### Key Concepts & Insights  
- **AI Fluency vs. Factual Accuracy**  
- **Academic Integrity & Plagiarism**  
- **Human Agency & Ethical Design**  
- **Data Privacy & Model Memory**

### Critical Reflection  
AI writing tools must be paired with human judgment and accountability. Ongoing ethical education is essential to build systems that **empower, not mislead**.

---

## Unit 9: CNN Activity & Development Project  
**Theme:** Image Classification with CIFAR-10  

### Related Learning Outcomes  
- Apply & evaluate ML techniques in real contexts.  
- Assess dataset suitability and challenges.  
- Build practical deep-learning models.

### Key Concepts & Insights  
- **Dataset Exploration:** `CIFAR-10` (32 × 32 × 3), class imbalance.  
- **Data Partitioning:** train/val/test 60 / 20 / 20 %.  
- **Reproducibility:** fixed random seeds, TensorFlow/Keras utilities.

### Critical Reflection  
Directly informed my final assignment—deepened skills in CNN implementation, dataset handling, and performance evaluation.

---

## Unit 11: Evaluating Model Performance  

**Activity Type:** Model Performance Measurement  

### Key Concepts & Insights  
- **Confusion Matrix** → precision, recall, accuracy, F1.  
- **ROC & AUC:** one test case AUC = **0.79**.  
- **Regression Metrics:** RMSE, MAE, R².

### Critical Reflection  
Experiments showed how kernel choice and noise affect generalisation. Careful parameter selection and clean data are vital for reliable models.

---
