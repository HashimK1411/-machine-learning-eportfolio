## 🧪 Individual Project: CNNs and Transfer Learning with CIFAR-10

### 🎯 Project Overview
This project explored the use of **Convolutional Neural Networks (CNNs)** and **Transfer Learning (MobileNetV2)** for image classification using the CIFAR-10 dataset. I worked individually to build, train, evaluate, and compare both approaches to understand their strengths and trade-offs in a real-world context.

---

### 🔨 My Contributions

- **Selected Track 2 (Deep Learning)**: Focused on CNNs and transfer learning for object recognition tasks.
- **Preprocessed Data**:
  - Normalised CIFAR-10 image pixel values to the range 0–1.
  - Resized images for MobileNetV2 input (96x96).
  - Split dataset into training (40K), validation (10K), and test (10K) sets.
- **Implemented a Baseline CNN** using TensorFlow/Keras:
  - 3 Conv layers + ReLU
  - MaxPooling
  - Dense + Softmax layer
  - Trained over 10 epochs with Adam optimiser
- **Developed Transfer Learning Model**:
  - Used pre-trained **MobileNetV2** (frozen base layers)
  - Added Global Average Pooling + Dense classification layer
  - Achieved higher accuracy with less training and overfitting
- **Evaluated Model Performance**:
  - Tracked training/validation accuracy
  - Created confusion matrix to assess per-class performance
  - Compared generalisation and convergence speed
- **Documented Key Findings**:
  - CNN achieved ~69% validation accuracy
  - MobileNetV2 achieved ~81% validation accuracy
  - Transfer learning generalised better and trained faster

---

### 📈 Key Learnings

- Gained hands-on experience with CNN architecture design and implementation.
- Understood the practical advantages of transfer learning for image recognition.
- Learned how to interpret training curves, evaluate model performance, and handle overfitting.
- Developed visual artefacts: accuracy plots, confusion matrix, and demo predictions.
- Reflected on the difference between building models from scratch and using pre-trained models for deployment.

---

### 🧩 Tools & Libraries

- **Python**, **TensorFlow/Keras**, **NumPy**, **Matplotlib**
- CIFAR-10 dataset via `keras.datasets`
- Jupyter Notebook for development and testing

---

### 📚 References

See [references.md](./references.md) for a complete list of sources used throughout this project.
