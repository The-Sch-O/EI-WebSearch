# EI-WebSearch

Dans le cadre de l'enseignement d'intégration, un moteur de recherche a été développé à partir des données extraites du formulaire de questions et réponses de "Stack Exchange" disponible à ce lien : https://archive.org/details/stackexchange.

Pour pouvoir exécuter le code, les fichiers doivent être extraits et placés dans un dossier nommé "data". Pour ce faire, veuillez suivre le tutoriel du Day1. Ensuite, vous devez exécuter toutes les cellules du code. Dans la dernière cellule, vous devez fournir la requête sous forme de chaîne de caractères en entrée de la variable "query", puis exécuter la cellule. En sortie du programme, vous obtiendrez les 10 meilleurs documents correspondant à la requête fournie, avec leur contenu.

/!\ Attention, la première éxecution du code peut durer assez longtemps (création de l'index inversé, entraînement avec scikit-learn et sentence_transformers)


## Structure de stockage des données

/data
    Badges.xml
    Comments.xml
    ...
    evaluation_search_engine_post_queries_ranking_EI_CS.xlsx
    # les fichiers suivants seront créés à la première éxecution du code afin de stocker les fichiers volumineux
    inverted_index.pickle
    embeddings.pkl
    ldamodel.pkl

