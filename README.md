# SafeBytes

**SafeBytes** Développement d’un système de détection de malwares combinant analyse statique et dynamique, avec un focus sur le comportement réseau des exécutables suspects. Intégration de la capture de trafic en temps réel via Scapy et Tshark afin d’extraire des caractéristiques comportementales (IP contactées, fréquence des connexions, usage de ports inhabituels, requêtes DNS). Utilisation de Python, TensorFlow et Scikit-learn pour entraîner un modèle de classification capable de distinguer les logiciels malveillants des fichiers légitimes. Ce projet s’inscrit dans une logique de cybersécurité proactive, en identifiant les menaces grâce à l’analyse du réseau et à l’IA

---

## 🛡️ Project Overview

- 🧠 Uses machine learning to detect malware based on file characteristics
- 🔍 Analyzes features like file size, entropy, API calls, and byte patterns
- ⚡ Focused on achieving high precision, recall, and overall detection accuracy
- 🖥️ Future goal: user-friendly file scanning tool with a simple interface

---

## 🚀 Features

- Malware vs. benign file classification
- Feature extraction and preprocessing
- Trainable and customizable ML models
- Model evaluation with accuracy, precision, recall, and AUC
- (Optional) Real-time file scanning through a simple GUI

---

## 📦 Tech Stack

- Python 3
- scikit-learn
- pandas
- numpy
- matplotlib / seaborn
- (Optional) Flask or Streamlit for GUI

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/a-naoufel/safebytes.git
   cd safebytes
