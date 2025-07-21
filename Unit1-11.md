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

### Reflection  
This activity helped me bridge theory with practice. It became clear that AI and digital transformation cannot be pursued without equal attention to ethical and legal safeguards. For machine learning professionals, this means not only understanding how to develop systems, but how to design them with integrity, security, and user trust at the core. The discussion also made me aware of how proactive risk assessment is vital in both cybersecurity and broader AI governance.

See [References.md](./References.md) for a complete list of sources used throughout this project.

---

## Unit 2: Industry 4.0 → 5.0  
**Activity Type:** Collaborative Discussion – Peer Responses  

### Summary of Activity  
Building on Unit 1, I engaged with peers on the transition from **Industry 4.0 to 5.0**. Discussions centred on how Industry 5.0 embeds *ethical, resilient, human-centric* values into technological adoption.

### Reflection  
The shift from Industry 4.0 to 5.0 isn’t just about new technologies—it’s a mindset change. It’s about embedding values like fairness, adaptability, and resilience into the very architecture of our digital systems. These reflections will inform how I approach both technical problem-solving and stakeholder responsibilities in future projects

See [References.md](./References.md) for a complete list of sources used throughout this project.

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
This unit bridged theory and code. Working with synthetic and real data revealed how correlation and regression vary across scenarios. Modifying datasets deepened my grasp of noise, overfitting, and model sensitivity which is key for future AI modelling.

See [References.md](./References.md) for a complete list of sources used throughout this project.

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
Clustering and similarity analysis are core to machine learning where patterns emerge without labels. Using visual and mathematical artefacts, I learned to segment data and compare binary features—skills vital for profiling, anomaly detection, and recommendations.

See [References.md](./References.md) for a complete list of sources used throughout this project.

---

## Units 5 & 6: Group Project – Predicting Airbnb Prices  
**Theme:** Collaborative ML Project on Real-World Data  

### Group Collaboration Overview  
- Weekly meetings (Units 1 → 6)  
- **Business Question:** Is there an optimal pricing point for maximising Airbnb occupancy rates and revenue, and how is this affected by neighbourhood and local amenities?

### Unit 5 Artefact – **EDA & Initial Model**  
- Data cleaning and exploratory analysis  
- Baseline linear regression  
- Learned the impact of feature selection and shared responsibilities.

### Unit 6 Artefact – **Final Report**  
- Model refinements and alternative configurations  
- Comprehensive paper: business context, pipeline, results, reflections.
- **Report Contents:** The submission outlined our complete pipeline—business context, data preparation, modelling approach, results analysis, and final reflections on the collaborative process.

### Reflection  
Working as part of a development team allowed me to apply machine learning theory in a practical, team-oriented setting. It also highlighted the importance of communication, mutual support, and adaptability when handling real-world datasets. This experience strengthened both my technical and interpersonal skills particularly in managing shared responsibilities and learning from peer feedback.

See [References.md](./References.md) for a complete list of sources used throughout this project.

---

## Unit 7: Introduction to Artificial Neural Networks  

### Part 1 – **Simple Perceptron**  
NumPy simulation of weighted sums + step activation.

### Part 2 – **Perceptron Learning: AND Gate**  
Implemented weight-update loop until perfect classification.

### Part 3 – **Multi-Layer Perceptron (MLP)**  
Showed how hidden layers and back-propagation extend learning capacity.

### Reflection  
Though I didn’t write or modify code, the guided activities reinforced key neural network concepts—input weighting, activation functions, supervised learning, and the shift from simple to layered models. This built a solid foundation for understanding and evaluating complex ANNs.

See [References.md](./References.md) for a complete list of sources used throughout this project.

---

## Units 8–10: Forum Reflection – AI-Assisted Writing  

### Summary of Activity  
Units 8–10 explored AI-assisted writing tools like ChatGPT and GPT-3. My post highlighted their potential and pitfalls. Citing Hutson (2021), I noted how fluent yet misleading outputs raise concerns about factual accuracy. Harati (2024) and Carobene et al. (2023) further warned of risks like plagiarism, misinformation, and weakened academic integrity without strong human oversight.

### Key Concepts & Insights  
- **AI Fluency vs. Factual Accuracy**  
- **Academic Integrity & Plagiarism**  
- **Human Agency & Ethical Design**  
- **Data Privacy & Model Memory**

###  Reflection  
This discussion pushed me to consider the academic, legal, and ethical dimensions of AI writing tools. While they can aid learning and streamline content creation, they must be used with human judgment and accountability. I now see the importance of ongoing education on ethical AI use—essential for building systems that empower, not mislead.

See [References.md](./References.md) for a complete list of sources used throughout this project.

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

### Reflection  
This activity directly contributed to my final assignment, reinforcing practical knowledge of CNN implementation, dataset handling, and model evaluation. This experience enhanced my problem-solving, coding fluency, and critical evaluation of model performance—core skills required for machine learning professionals.

See [References.md](./References.md) for a complete list of sources used throughout this project.

---

## Unit 11: Evaluating Model Performance  

**Activity Type:** Model Performance Measurement  

### Key Concepts & Insights  
- **Confusion Matrix** → precision, recall, accuracy, F1.  
- **ROC & AUC:** one test case AUC = **0.79**.  
- **Regression Metrics:** RMSE, MAE, R².

### Reflection  
This activity showed how model tuning and data quality affect performance. Changing the kernel type altered pattern recognition and generalisation, while adding noise revealed sensitivity to irrelevant features. These experiments highlighted the need for careful parameter selection and clean data.

See [References.md](./References.md) for a complete list of sources used throughout this project.

---
