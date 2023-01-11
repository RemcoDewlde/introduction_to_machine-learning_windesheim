# Introduction to machine-learning Windesheim
Het idee is om aan de hand van een aantal waarden in een csv bestand te kunnen voorspellen/achterhalen welke rating een game zou moeten/kunnen krijgen.
## Dataset
De dataset bestaat uit twee csv bestanden die afkomsting zijn van Kaggle. De data zou afkomsting moeten zijn van het Amerikaanse Entertainment Software Rating Board.
![ESRB rating](/assets/Rating.svg)
Link: [dataset Kaggle](https://www.kaggle.com/datasets/imohtn/video-games-rating-by-esrb)

## Tests
Random forrest heeft een aantal variablen zoals `max_depth`, `test_size` en `n_estimators`. Om goede waarde voor deze variablen te gebruiken zijn verschillende testen opgezet om dit te bepalen. De bevindingen uit deze testen zijn gebruikt in het `random-forrest.ipynb` bestand.