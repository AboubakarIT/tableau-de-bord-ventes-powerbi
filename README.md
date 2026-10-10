# Tableau de bord des ventes (Power BI)

Tableau de bord interactif d'analyse des ventes d'un magasin, réalisé avec Power BI Desktop.



![Aperçu](apercu.png)
<img width="748" height="344" alt="Capture d’écran 2026-10-09 235251" src="https://github.com/user-attachments/assets/48d83253-2a0e-4d8f-8fa6-cf38173d3cda" />



## Données
Jeu de données « Superstore Sales » (Kaggle) : 9 800 lignes, 18 colonnes, ventes de 2015 à 2018.

## Nettoyage (Power Query)
- Vérification des en-têtes et des types de données (dates, nombres, texte)
- Code postal converti en texte
- Colonne Sales corrigée : lecture des nombres au format anglais (point décimal)

## Indicateurs
- Chiffre d'affaires : 2,26 M
- Commandes : 4 922
- Clients : 793
- Panier moyen : 459,48 (mesure DAX : somme des ventes / nombre de commandes distinctes)

## Visuels
- Ventes par mois (courbe)
- Ventes par catégorie (barres)
- Ventes par région (barres)
- Filtres interactifs : année et catégorie

## Outils
Power BI Desktop, Power Query, DAX

## Auteur
Aboubakar Koné, étudiant en Licence 3 Réseaux et Sécurité Informatique (UVCI, Abidjan)
