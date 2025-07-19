 

Unit 1: Introduction to Machine Learning

Activity Type: Collaborative Discussion Theme: The 4th Industrial Revolution

 

Summary of Activity

In this activity, I explored how technological advancement, while transformative, brings about critical cybersecurity and governance concerns. I analysed the 2021 T-Mobile data breach as a case study to show how increased digital interconnectivity through AI, cloud computing, and big data can introduce significant vulnerabilities when cybersecurity is not properly embedded into digital infrastructure.

Key Concepts and Insights

Complex Systems and Vulnerabilities

Skills Gaps in Industry 4.0

The Shift to Industry 5.0

 

Critical Reflection

This activity helped me bridge theory with practice. It became clear that AI and digital transformation cannot be pursued without equal attention to ethical and legal safeguards. For machine learning professionals, this means not only understanding how to develop systems, but how to design them with integrity, security, and user trust at the core. The discussion also made me aware of how proactive risk assessment is vital in both cybersecurity and broader AI governance.

 

 

Unit 2: Industry 4.0 vs. Industry 5.0

 

Activity Type: Collaborative Discussion – Peer Responses

Summary of Activity

In Unit 2, building on Unit 1, the focus shifted to the transition from Industry 4.0 to 5.0. I engaged with two peers’ posts exploring real-world tech adoption. Discussions centred on how Industry 5.0 enhances its predecessor with ethical, resilient, and human-centric values.

Critical Reflection:

The shift from Industry 4.0 to 5.0 isn’t just about new technologies—it’s a mindset change. It’s about embedding values like fairness, adaptability, and resilience into the very architecture of our digital systems. These reflections will inform how I approach both technical problem-solving and stakeholder responsibilities in future projects

 

Unit 3: Correlation and Regression



Theme: Understanding Linear and Nonlinear Relationships in Data

In Unit 3, we moved into practical, hands-on applications of correlation and regression analysis—critical tools in data science and machine learning. I explored four Python programmes, each focusing on a different statistical technique. Below is a summary of each artefact, along with the modifications I applied and what I learned from them.

 

**Programme 1: Pearson Correlation with Random Data**

Initial Observation: data2 was linearly dependent on data1, yielding a strong correlation (r = 0.888).

Modification Applied: Increased randomness and reduced dependency between datasets.

Result: The correlation dropped to r = 0.098, demonstrating how noise impacts statistical relationships.

 

Programme 2: Linear Regression with Noisy Data

Initial Observation: A clear negative trend existed (r = -0.759).

Modification Applied: I introduced random noise into the y values using np.random.randint().

Result: Correlation dropped to r = -0.302 and the predicted value at x = 10 changed to 90.45.

 

** Programme 3: Multiple Linear Regression**

Data Used: A CSV dataset with features like weight, volume, and CO₂ emissions.

Result: The model's learned coefficients were:

Weight: 0.00755

Volume: 0.00781

Prediction: A car with 2300kg and 1300cm³ volume emits ~107.21g of CO₂. Increasing the weight to 3300kg raised this to ~114.76g.

 

** Programme 4: Polynomial Regression and R² Evaluation**

Initial Model Fit: R² = 0.94, indicating a strong fit.

Modification Applied: I added more noise to the y-values.

Result: R² dropped to 0.76 and predicted speed at x = 17 reduced from ~88.87 to ~81.18.

 

Reflection

This unit bridged theory and code. Working with synthetic and real data revealed how correlation and regression vary across scenarios. Modifying datasets deepened my grasp of noise, overfitting, and model sensitivity—key for future AI modelling.

 

Unit 4: Clustering and Similarity

 

Unit 4 covered unsupervised learning, focusing on clustering and similarity metrics. I used K-Means to group unlabeled data and applied Jaccard similarity to compare binary attributes—key techniques for pattern recognition, recommendations, and customer segmentation.

Artefact 1: K-Means Clustering

Activity: A visual demonstration of the K-Means algorithm was explored. The animation clearly illustrated how centroids shift iteratively and how points are grouped into clusters based on proximity.

Reflection: This visual clarified how unsupervised clustering groups users by behaviour or preference. It also introduced key evaluation metrics: intra-cluster similarity and inter-cluster distance.

 

** Artefact 2: Jaccard Coefficient**

Activity: I manually calculated the Jaccard similarity for binary vectors representing patient test results.

Resulting Values:

(Jack, Mary) = 0.33

(Jack, Jim) = 0.67

(Jim, Mary) = 0.75

 

Reflection

Clustering and similarity analysis are core to machine learning where patterns emerge without labels. Using visual and mathematical artefacts, I learned to segment data and compare binary features—skills vital for profiling, anomaly detection, and recommendations.

 

Unit 5 & 6 – Group Project: Predicting Airbnb Prices

 

Theme: Collaborative Machine Learning Project on Real-World Data

Our team project, running from Units 1 to 6, focused on building a predictive model for Airbnb prices using supervised learning. This marked a shift from individual tasks to collaborative, end-to-end application of our learning.

** Group Collaboration Overview**

Meetings: We held regular weekly meetings from Unit 1 onwards to discuss our progress, divide tasks, and align on tools and approaches.

Business Question: The group agreed to investigate what factors most influence Airbnb pricing—e.g., location, number of beds, review scores.

 

Unit 5 Artefact: Model Development & EDA

Activity: We collaboratively performed data cleaning, exploratory data analysis (EDA), and initial linear regression modelling.

Learning Outcomes:

Understood the effect of feature selection on pricing.

Improved collaboration skills by sharing responsibilities such as visualisation, interpretation, and preprocessing.

Reinforced the value of real-world data handling and regression modelling techniques.

 

** Unit 6 Artefact: Final Group Report**

Activity: We refined the model, tested alternative configurations, and consolidated findings into a detailed report.

Report Contents: The submission outlined our complete pipeline—business context, data preparation, modelling approach, results analysis, and final reflections on the collaborative process.

** Reflection**

Working as part of a development team allowed me to apply machine learning theory in a practical, team-oriented setting. It also highlighted the importance of communication, mutual support, and adaptability when handling real-world datasets. This experience strengthened both my technical and interpersonal skills particularly in managing shared responsibilities and learning from peer feedback.

 

 

Unit 7 – Introduction to Artificial Neural Networks

In Unit 7, I studied core ANN principles, including the perceptron, logic gate learning, and an intro to Multi-Layer Perceptrons (MLPs). Through guided e-portfolio activities, I focused on understanding neural model mechanisms and behaviours.

** Part 1: Simple Perceptron Implementation**

The first activity showed how a single-layer perceptron sums weighted inputs and applies a step function. Using NumPy, I simulated inputs and adjusted weights to observe how activation changes, reinforcing the link between inputs and threshold logic.

Part 2: Perceptron Learning and the AND Gate

The next activity involved training a perceptron to solve the AND logic gate using NumPy. Applying the weight update rule in a learning loop, the model gradually improved until it correctly classified all AND inputs.

Part 3: Multi-Layer Perceptron (MLP)

The final task used a Multi-Layer Perceptron (MLP) to model an AND gate, showing how hidden layers enable learning beyond simple patterns. It introduced backpropagation, which adjusts internal weights, laying the groundwork for more advanced neural networks.

Reflection

Though I didn’t write or modify code, the guided activities reinforced key neural network concepts—input weighting, activation functions, supervised learning, and the shift from simple to layered models. This built a solid foundation for understanding and evaluating complex ANNs.

 

Unit 8–10: Collaborative Forum Reflection – AI-Assisted Writing

 

Summary of ActivityUnits 8–10 explored AI-assisted writing tools like ChatGPT and GPT-3. My post highlighted their potential and pitfalls. Citing Hutson (2021), I noted how fluent yet misleading outputs raise concerns about factual accuracy. Harati (2024) and Carobene et al. (2023) further warned of risks like plagiarism, misinformation, and weakened academic integrity without strong human oversight.

Key Concepts and Insights

• AI Fluency vs. Factual Accuracy• Academic Integrity and Plagiarism Risks• Human Agency and Ethical Design• Data Privacy and Model Memory:

 

Critical ReflectionThis discussion pushed me to consider the academic, legal, and ethical dimensions of AI writing tools. While they can aid learning and streamline content creation, they must be used with human judgment and accountability. I now see the importance of ongoing education on ethical AI use—essential for building systems that empower, not mislead.

 

Unit 9 CNN activity and Development Individual Project: PresentationTheme: Applying CNNs for Image Classification with CIFAR-10Related Learning Outcomes:

·       Apply and evaluate machine learning techniques in real-world contexts, especially under technical risk and uncertainty.

·       Assess dataset suitability and challenges for machine learning applications.

·       Build practical deep learning models for image recognition tasks.

 

Key Concepts and Insights

·       **Dataset Exploration: **CIFAR-10 posed real-world challenges like class imbalance and low resolution. I explored image shapes (32×32×3) and visualised data using matplotlib and array_to_img.

·       **Data Partitioning: **Splitting data into training, validation, and test sets (e.g. 60%-20%-20%) helped ensure model generalisability.

·       **Reproducibility: **I used random seeds and TensorFlow/Keras utilities to maintain consistent training outcomes.

Critical Reflection

This activity directly contributed to my final assignment, reinforcing practical knowledge of CNN implementation, dataset handling, and model evaluation. This experience enhanced my problem-solving, coding fluency, and critical evaluation of model performance—core skills required for machine learning professionals.

 

Unit 11 Artefact: Evaluating Model Performance in Machine Learning

Activity Type: Model Performance MeasurementRelated Learning Outcomes:

Evaluate machine learning models using appropriate performance metrics.

Apply theoretical and practical knowledge to assess model accuracy, robustness, and fairness.

Interpret the impact of evaluation results to inform future modelling decisions.

 

Key Concepts and Insights

Confusion Matrix & Derived Metrics:The confusion matrix broke down prediction outcomes into true/false positives and negatives. From this, I calculated precision, recall, accuracy, and F1 scores to evaluate model performance.

ROC Curve and AUC:The ROC curve showed the trade-off between true and false positives. One test case had an AUC of 0.79, indicating moderate performance and highlighting the value of threshold-independent metrics under class imbalance.

Regression Metrics (RMSE, MAE, R²):Model evaluation was extended to regression tasks using error-based metrics. RMSE and MAE quantified the deviation between predicted and true values, while R² indicated the proportion of variance explained by the model.

 

 

Critical Reflection

This activity showed how model tuning and data quality affect performance. Changing the kernel type altered pattern recognition and generalisation, while adding noise revealed sensitivity to irrelevant features. These experiments highlighted the need for careful parameter selection and clean data.