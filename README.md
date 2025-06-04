# Classification des commentaires Facebook & Segmentation des prospects - Banque Zitouna

Ce projet a été réalisé dans le cadre de mon Projet de Fin d'Études pour l'obtention du diplôme d'ingénieur en Statistique et Analyse de l'Information, en partenariat avec la **Banque Zitouna**.

## 🎯 Objectif

- Collecter automatiquement les commentaires publiés sur la page Facebook de la banque Zitouna.
- Classifier ces commentaires en utilisant le **Traitement Automatique du Langage Naturel (NLP)**.
- Segmenter les prospects selon leurs besoins et intentions afin d’identifier les profils intéressants pour la banque.
- Déployer un **chatbot Facebook Messenger** pour interagir automatiquement avec les prospects qualifiés.

## 🧰 Technologies & outils

- **Python** (NLTK, scikit-learn, pandas, selenium, wordcloud, plotly)
- **MongoDB** pour la base de données NoSQL
- **MLflow** pour le suivi des expériences de machine learning
- **Deep Learning** : RNN, LSTM
- **Django + Ngrok** pour le déploiement du chatbot Messenger
- **Web scraping** avec Selenium

## 🧠 Modélisation

- Prétraitement des textes (nettoyage, tokenisation, suppression des emojis, stopwords)
- Classification des commentaires en 4 catégories :
  - `Autre`
  - `Particulier`
  - `Professionnel`
  - `Service`
- Segmentation des prospects à partir des commentaires et données publiques de leurs profils Facebook
- Modèles testés : **LSTM**, **RNN**, **Random Forest**, **XGBoost**, **Régression Logistique**

## 🤖 Chatbot Messenger

- Intégré à la page Facebook de la banque
- Capable de répondre automatiquement aux questions courantes
- Connecté aux résultats de classification NLP pour orienter les réponses

## 📊 Résultats

- Amélioration de l’identification des prospects qualifiés
- Création d’un pipeline complet : scraping → base MongoDB → NLP → segmentation → chatbot
- Analyse comparative des modèles (F1-score, accuracy, recall, ROC, etc.)

## 📎 Rapport

📄 [Rapport complet du projet (PDF)](./Rapport%20Final.pdf)

📽️ [Présentation avec démo vidéo page 28 (chaque diapo est numéroté à gauche en bas, diapo 32)(Google Drive)]([https://drive.google.com/your-link-ici](https://docs.google.com/presentation/d/19lz_AMs2MRc4zeg2gg8HAWlmzJOBAJgR/edit?usp=sharing&ouid=112678636381172917271&rtpof=true&sd=true))

## 👨‍💻 Réalisé par

Mohamed Abderrahim Jridi  
Encadré par :  
- Mr. Farouk Mhamdi (Université)  
- Mr. Marwen Ben Nasr (Banque Zitouna)  
Année universitaire 2021/2022
