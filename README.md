# 🔐 Système de Détection d’Intrusion pour les Réseaux IoT basé sur Deep Active Learning

## 📌 Description

Ce projet présente le développement d’un **système de détection d’intrusion (IDS)** pour les réseaux IoT, basé sur une approche innovante combinant :

* 🧠 Deep Learning (CNN)
* 🎯 Active Learning

L’objectif principal est d’améliorer la détection des attaques tout en réduisant la dépendance aux données étiquetées coûteuses.

Ce travail a été réalisé dans le cadre d’un mémoire de Master en Informatique (Réseaux, Mobilité et Systèmes Embarqués) à l’Université Mouloud Mammeri de Tizi-Ouzou. 

---

## 🚀 Objectifs du projet

* Détecter efficacement les intrusions dans les réseaux IoT
* Réduire le besoin en données étiquetées grâce à l’apprentissage actif
* Améliorer les performances des IDS traditionnels
* Adapter le système aux nouvelles menaces

---

## 🧠 Technologies utilisées

* Python
* Deep Learning (CNN 1D)
* Active Learning
* Machine Learning
* Dataset IoTID20
* Bibliothèques :

  * TensorFlow / Keras
  * Scikit-learn
  * Pandas / NumPy
  * Matplotlib

---

## 🏗️ Architecture du système

Le système repose sur deux phases principales :

### 🔹 Phase d’entraînement

* Prétraitement des données
* Entraînement du modèle CNN
* Sélection intelligente des données (Active Learning)

### 🔹 Phase de détection

* Analyse du trafic IoT
* Classification :

  * Normal
  * Attaque

---

## 📊 Dataset

Le projet utilise le dataset **IoTID20**, qui contient :

* Données réseau IoT
* Différents types d’attaques :

  * DoS / DDoS
  * MITM
  * Spoofing
  * Attaques réseau diverses 

---

## ⚙️ Prétraitement des données

* Nettoyage des données
* Encodage des variables
* Normalisation
* Sélection des caractéristiques

---

## 🤖 Modèle utilisé

* Modèle : **CNN 1D**
* Capable de :

  * Extraire des patterns complexes
  * Détecter les anomalies réseau

---

## 🔁 Apprentissage actif

Le système utilise une stratégie d’**Active Learning** pour :

* Sélectionner les données les plus informatives
* Réduire le coût d’annotation
* Améliorer progressivement les performances

---

## 📈 Résultats

* Amélioration des performances avec Active Learning
* Réduction du taux d’erreur
* Meilleure généralisation du modèle 

---



---

## ▶️ Installation

```bash
git clone https://github.com/ton-username/ids-iot-active-learning.git
cd ids-iot-active-learning
pip install -r requirements.txt
```

---

## ▶️ Utilisation

```bash
Utiliser Anaconda ou Google Colab
```

---

## 🔒 Sécurité IoT (Contexte)

Les réseaux IoT sont vulnérables à plusieurs attaques :

* Attaques passives (écoute, analyse trafic)
* Attaques actives :

  * DoS / DDoS
  * Man-in-the-Middle
  * Injection de données 

Ce projet vise à renforcer la sécurité face à ces menaces.

---

## 👨‍💻 Auteurs

* **Aliche Omar**
* **Loudahi Khaled**

---

## 🎓 Encadrement

* Mme AIT ISSAD Hassina (Promotrice)

---

## 📜 Licence

Ce projet est destiné à un usage académique et de recherche.

---

## ⭐ Remarque

Ce projet s’inscrit dans le domaine de :

* Cybersécurité IoT
* Intelligence Artificielle
* Détection d’anomalies réseau


