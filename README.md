# Introduction to machine-learning Windesheim
![Vscode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
___

Het idee is om aan de hand van een aantal waarden in een csv bestand te kunnen voorspellen/achterhalen welke rating een game zou moeten/kunnen krijgen.
## Dataset
![ESRB rating](/assets/esrb_rating.svg)

De dataset bestaat uit twee csv bestanden die afkomsting zijn van Kaggle. De data zou afkomsting moeten zijn van het Amerikaanse Entertainment Software Rating Board.
Link: [dataset Kaggle](https://www.kaggle.com/datasets/imohtn/video-games-rating-by-esrb)

# Classifiers
Bij het maken is gebruik gemaakt van een aantal classifiers. Deze zijn allemaal te vinden in naam bijpassende map.
Bij elk van de classifiers is er aan het eind van de notebook een rapport gegenereerd. Aan de hand van deze rapporten zal het mogelijk zijn om te bepalen welke classifier het beste werkt. 

## Random Forest
Random forest heeft een aantal variablen zoals `max_depth`, `test_size` en `n_estimators`. Om goede waarde voor deze variablen te gebruiken zijn verschillende testen opgezet om dit te bepalen. De bevindingen uit deze testen zijn gebruikt in het `radnom_forest/random-forest.ipynb` bestand.
## k-NN
k-NN heeft een aantal variablen Om goede waarde voor deze variablen te gebruiken zijn verschillende testen opgezet om dit te bepalen. De bevindingen uit deze testen zijn gebruikt in het `machine_learning` bestand.
## Decision tree
Decision tree heeft een aantal variablen Om goede waarde voor deze variablen te gebruiken zijn verschillende testen opgezet om dit te bepalen.

## Support Vector Machine
Support Vector Machine heeft een aantal variablen Om goede waarde voor deze variablen te gebruiken zijn verschillende testen opgezet om dit te bepalen.

## Ensamble Voting Classifier
De bovenstaande classifiers zijn gebruikt om een ensamble voting classifier te maken. Deze classifier is opgezet met alle ideaale variablen van de bovenstaande classifiers.


