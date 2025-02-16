Ce projet utilise Hugging Face Transformers pour classifier automatiquement des verbatims clients en fonction de thèmes prédéfinis et analyser leur sentiment (positif ou négatif).

- Classification des concepts : Attribution de thèmes aux verbatims en utilisant un modèle Zero-Shot Classification avec un seuil de classification à 0.95.
- Analyse de sentiment : Détermination du ton des commentaires avec un modèle de Sentiment Analysis.
- Optimisation : Détection automatique des concepts grâce à une liste de mots-clés.
- Traitement par batch : Gestion efficace de grands ensembles de données.
- Visualisation des résultats

Modèles Utilisés : 
- Classification des concepts : facebook/bart-large-mnli
- Analyse de sentiment : distilbert-base-uncased-finetuned-sst-2-english
