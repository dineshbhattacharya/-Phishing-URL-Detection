# 🛡️ Phishing URL Detection using Nature-Inspired Algorithms

## 🧠 Description

This project was developed during a **Research Internship (May–July 2024)** at the **Indian Institute of Engineering Science and Technology (IIEST), Shibpur**, with the goal of enhancing cybersecurity by detecting phishing websites using **nature-inspired algorithms**.

The system applies **Genetic Algorithms (GA)** and **Particle Swarm Optimization (PSO)** to classify URLs as malicious or legitimate. It extracts and analyzes several URL-based features—such as domain age, lexical patterns, and HTTPS presence—to build a lightweight, fast, and scalable detection pipeline.

The final model achieved **96.8% accuracy** and can process over **10,000 URLs per minute**, making it suitable for browser integration and real-time protection.

---

## 🚀 Features

- ✅ **High Detection Accuracy**  
  Achieved **96.8% classification accuracy** on benchmark datasets using GA and PSO.

- ✅ **Real-Time URL Processing**  
  Capable of handling **10,000+ URLs/min** with minimal memory and CPU footprint.

- ✅ **Feature Extraction Engine**  
  Extracts key features such as:
  - URL length
  - Domain age
  - Presence of HTTPS
  - IP usage in domain
  - Number of subdomains
  - Special characters and lexical complexity

- ✅ **Scalable & Lightweight**  
  Designed for seamless integration into browser extensions or enterprise firewalls.

---

## 🧪 Algorithms Used

- 🧬 **Genetic Algorithm (GA)** — Used for feature selection and classification.  
- 🕊️ **Particle Swarm Optimization (PSO)** — Optimized model parameters for improved accuracy and speed.

---

## 📁 Project Structure

```plaintext
phishing-url-detector/
├── src/
│   ├── feature_extraction.py     # Extracts features from URLs
│   ├── genetic_algorithm.py      # GA-based classifier
│   ├── pso_classifier.py         # PSO-based classifier
│   ├── train_model.py            # Model training pipeline
│   └── evaluate.py               # Evaluation metrics and accuracy checks
│
├── data/
│   └── urls.csv                  # Phishing and legitimate URL dataset
│
├── models/
│   └── trained_model.pkl         # Saved classifier
│
├── notebook/
│   └── analysis.ipynb            # Experimentation and visualizations
│
├── requirements.txt              # Python dependencies
└── README.md                     # Project overview and documentation
```
---

## 📈 Results
🎯 96.8% detection accuracy on phishing vs. legitimate URLs

⚡ Real-time throughput: over 10,000 URLs per minute

🔒 Significant improvements in proactive threat detection
---
## 📌 Future Improvements
🌐 Deploy as a browser extension for Chrome/Firefox

🧠 Add deep learning models (e.g., LSTM or CNN) for comparison

🗃️ Train on larger and more diverse datasets for generalization
---
## 🛠 Tools & Technologies
🐍 Python

📦 Scikit-learn, Pandas, NumPy

📊 Matplotlib, Seaborn (for visualization)

🧪 Custom implementations of GA & PSO
---
## 📫 Contact

For questions or collaboration:  
**Dinesh Bhattacharya**  
📧 dineshbhattacharya2002@gmail.com
🔗 [LinkedIn / Portfolio link if applicable]

---
⚠️ Note: This project was part of academic research and is intended for demonstration and experimental use. Further tuning is recommended for deployment in production environments.
