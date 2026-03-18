# Économétrie : Analyse de la demande d'électricité en Irlande

## Présentation du projet
Ce projet consiste en une étude approfondie de la demande d'électricité en Irlande par le biais de l'économétrie des séries temporelles. L'objectif est de caractériser la dynamique de la série, d'identifier ses composantes et de tester sa stationnarité en tenant compte des potentielles ruptures structurelles.

## Méthodologie Statistique
L'analyse est structurée autour de plusieurs étapes clés :

### 1. Identification du processus
* **ACF (Autocorrelation Function)** : Analyse de la corrélation globale pour détecter la saisonnalité et la persistance.
* **PACF (Partial Autocorrelation Function)** : Identification de l'ordre des processus autorégressifs (AR).

### 2. Tests de Racines Unitaires et de Ruptures (Ru)
Quatre tests fondamentaux ont été réalisés pour vérifier la stationnarité :
* **DF (Dickey-Fuller)** : Test de base pour la présence d'une racine unitaire.
* **ADF (Augmented Dickey-Fuller)** : Test gérant l'autocorrélation des résidus.
* **ZA (Zivot-Andrews)** : Test de racine unitaire autorisant une rupture structurelle endogène sur la tendance ou la constante.
* **LS (Lumsdaine-Papell / Lee-Strazicich)** : Test avancé prenant en compte plusieurs ruptures structurelles.

## Technologies utilisées
* **Langage** : R
* **Librairies** : `urca`, `tseries`, `ggplot2`, `forecast`
* **Format** : R Markdown (`.Rmd`) pour une analyse reproductible.

## Auteur
* Andréa Saint Paul
