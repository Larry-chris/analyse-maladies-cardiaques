# **Analyse exploratoire des données sur les maladies cardiaques**

## **1. Contexte du projet**
Les maladies cardiaques sont l'une des principales causes de mortalité dans le monde. La connaissance des facteurs de risques associés est nécessaire pour une meilleure prévention.

Ce projet a pour but de réaliser une analyse exploratoire approfondie du célèbre jeu de données "Heart Disease" de l'UCI. En tant qu'étudiant en médecine et passioné par la science des données, mon objectif est de combiner une approche statistique rigoureuse avec une interprètation clinique pertinente pour dégager des facteurs de risques plus significatifs de la présence d'une maladie cardiaque.

## **2. Jeu de données**
Les données proviennent du **"Heart Disease UCI** ,collectées à partir de quatre bases de données (Cleveland, Hungary, Switzerland et VA Long Beach). Le jeu de données complet contient **920 observations** et **16 variables cliniques et démographiques**.
+ Source : https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data
+ Variable cible : num (diagnostic de la maladie cardiaque allant de 0 (absence de maladie) à 4 (stade avancé de la maladie))

## **3. Méthodologie**
L'analyse a été structuré en cinq étapes :
+ L'**inspection des données** : pour une évaluation initiale des données et la détection des problèmes
+ **Nettoyage approfondi** qui comprend :
  + la gestion des valeurs manquantes
  + la vérification de l'existence de doublons
  + la correction des types de données
  + et la gestion stratégique des valeurs aberrantes
+ L'**analyse univariée** : pour une exploration des variables étudiées
+ L'**analyse bivariée ou multivariée** : pour la recherche des relations entre les différentes variables pour identifier les corrélations les plus fortes avec la présence de maladie cardiaque.

## 4. Principaux résultats et hypoyhèses 
Cette analyse a permis de mettre en évidence plusieurs facteurs de risque potentiels :
+ **Facteurs démographique et clinique majeurs :**
  + L'**âge avancé** et une **tension artérielle élevée** sont fortement corrélés à une présence accrue des maladies cardiaques.
  + Une **glycémie à jeun élevée** semble être un indiacteur.
+ **Indicateurs au repos :**
  + La présence d'**une anomalie ST-T à l'électrocardiogramme au repos** est associée à une probabilité plus élevée de maladie .
  + Les patients présentant un **défaut (fixe ou réversible) au test de stress au thallium** ont un risque très élevé (plus de 75% atteints)
+ **Indicateurs à l'effort physique :**
  + Une **fréquence cardiaque maximale faible** durant l'effort est un indicateur de risque.
  + Une **dépression significative , ainsi qu'une pente plate ou descendante du segment ST** sont fortement associés à la maladie.
  + Le **déclenchement d'une angine de poitrine à l'effort** est un indicateur également.
+ **Facteurs les moins déterminants :**
  + Paradoxalement, le type de douleur thoracique n'est pas un indicateur fiable, la majorité des patients malades étant asymptomatique.
  + La cholestérolémie également ne montrait pas de corrélation claire ou directe avec la présence de maladie cardiaque.

## **5. Outils et technologies utilisés**
Ce projet a entièrement été réalisé en Python dans un environnement Jupyter Notebook. Les outils utilisés sont : 
+ **Analyse des données** : Pandas,Numpy
+ **Visualisation des données** : Matplotlib,Seaborn
+ **Gestion de version** : Git et GitHub

## **6. Comment utiliser ce projet ?**
+ Clonez le sur votre machine local avec la commande suivante:
git clone https://github.com/Larry-chris/analyse-maladies-cardiaques.git
+ Installez les dépendances nécessaires :
pip install -r requirements.txt
+ Ouvrez le notebook EDA_heart_diceases_uci.ipynb dans Jupyter Notebook pour explorer l'analyse complète.

## **7. Contact**
Je suis ouvert à la discussion,aux retours et aux opportunités de collaboration.
+ Profil Linkedln : Chris Larry BOKO
+ Email : bokolarry1@gmail.com
