# Analyse de Sentiments (Sentiment Analysis)
# Description
Ce projet implémente une application d'analyse de sentiments qui permet aux utilisateurs de soumettre du texte en français ou en anglais et de recevoir une prédiction sur le sentiment associé à ce texte.

# Fonctionnalités
Prend en charge le texte en français et en anglais.
Utilise des modèles de deep learning pour prédire le sentiment du texte.
Interface utilisateur conviviale avec Streamlit.
#  Modele
Un modèle d'analyse de sentiments a été utilisé pour classer les phrases en deux catégories : "Sentiment positif" et "Sentiment négatif".
Le modèle a été formé à l'aide de données provenant du fichier sentiment_dataset.csv en utilisant le réseau de neurones profonds. Vous trouverez les modèle enregistré [ici ](https://drive.google.com/drive/folders/15Rwqe_HBWnky8x-eLuWciAhJkM2ahUs8?usp=sharing)

# Fichiers Importants
app.py: Fichier principal de l'application Streamlit.
util.py: Fichier contenant des fonctions utilitaires pour configurer l'application.
model: Dossier contenant le modèle pré-entraîné et les fichiers associés.

# Comment utiliser l'application

1.Accédez à l'application en suivant le lien : [Lien vers l'Application.](https://major174-lydie-app-oxykag.streamlit.app/)

2.Entrez du texte selon votre choix (français ou anglais) dans la zone de texte prévue.

3.Cliquez sur le bouton "Predict" pour obtenir la prédiction.

4.La prédiction sera affichée avec des informations sur la probabilité associée à la présence du sentiment positif ou négatif.

# Remarques
1.Assurez-vous que le texte saisi est clair et exprime correctement le sentiment que vous souhaitez analyser.

2.Les résultats de la prédiction sont fournis à titre informatif uniquement. Ce modèle ne remplace pas l'expertise humaine, consultez un professionnel de l'analyse linguistique pour une interprétation précise.
