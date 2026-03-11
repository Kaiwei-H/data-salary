# Salary Prediction

Technologies : Python, Pandas, Scikit-learn, SHAP.

Ce projet vise à modéliser et prédire les salaires dans le domaine de la data science à partir d’un dataset d’environ **150 000 observations**.

Les données ont été analysées et prétraitées avec **Python (Pandas, NumPy)** : nettoyage, encodage des variables catégorielles et création de variables explicatives liées à l’expérience, la localisation et le poste.

Des modèles de machine learning ont été développés et comparés :

- **Decision Trees**
- **MLP (Multi-Layer Perceptron)**

Les performances des modèles ont été évaluées sur un jeu de test à l’aide de la métrique **MAE**.

Résultat principal :

- **MAE ≈ 40 000 USD**

L’analyse d’interprétabilité avec **SHAP** a permis d’identifier les variables les plus influentes, notamment l’expérience professionnelle, la localisation et le poste occupé.
