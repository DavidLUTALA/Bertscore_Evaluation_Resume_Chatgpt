# Bertscore_Evaluation_Resume-_Chatgpt
Ce projet utilise BERTScore pour évaluer la performance entre des paragraphes des résumés rédigé par un expert et celui formulé par chatgpt. Il permet d'obtenir une mesure précise de la proximité sémantique entre un texte source de l'expert et un texte cible, en exploitant la puissance des modèles pré-entraînés de type BERT , RoBERTa , et XLNet.

---

### 🚀 Objectifs du projet
- Comparer automatiquement des paragraphes rédigés par expert et leurs résumé généré par chatGPT.
- Fournir une évaluation avancée de la qualité des résumés générés.
- Expérimenter différentes architectures de modèles BERT pour améliorer l'évaluation.
- Offrir un outil flexible pour analyser la similarité textuelle dans divers contextes (NLP, résumé automatique, détection de paraphrases).

---

## 📊 Utilisation du Notebook
1. Charger les bibliothèques nécessaires :
   - pandas, torch, transformers, bert_score.
2. Lisez les données textuelles (fichiers CSV, JSON ou TXT).
3. Nettoyer et prétraiter les paragraphes .
4. Appliquer BERTScore pour évaluer la similarité.
5. Analyser les résultats et générer des visualisations .

---

## 📈 **Résultats et Visualisation**  

- Les scores de similarité sont enregistrés dans `results/bert_scores.csv`.  
- Une **matrice de heatmap** peut être générée pour visualiser la proximité entre les phrases.  
- Un rapport peut être exporté en **Excel/CSV** pour analyse.  

Exemple de sortie (score BERTScore) :  
| Paragraphe | Résumé | BERTScore (F1) |
|------------|--------|----------------|
| "Le climat change rapidement." | "Le réchauffement climatique s’accélère." | **0.89** |
| "Les voitures électriques gagnent en popularité." | "Les véhicules électriques sont de plus en plus adoptés." | **0.92** |

---

## 📜 **Dépendances et Versions**  

Ce projet a été testé avec :  

| Package | Version |
|---------|---------|
| Python  | 3.8+   |
| torch   | 1.10+  |
| transformers | 4.10+  |
| bert_score  | 0.3.11  |
| pandas  | 1.3.3  |

---

## 📜 **Licence**  

Ce projet est sous licence MIT - voir le fichier `LICENSE` pour plus de détails.  

---

## 📞 **Contact**  

Si tu as des questions ou suggestions, n'hésite pas à me contacter !  
📧 **Email** : [davidlutala0@gmail](mailto:davidlutala0@gmail])  
🐙 **GitHub** : [DavidLutala](https://www.github.com/DavidLUTALA)  

---
