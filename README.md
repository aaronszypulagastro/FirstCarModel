# FirstCarModel 

Dieses Projekt ist mein erstes Machine-Learning-Modell mit TensorFlow/Keras.  
Ziel ist es, den aktuellen Preis eines Autos anhand verschiedener Merkmale wie km-Stand, PS, Zustand und weiteren Features vorherzusagen.

##  Daten
- Die Trainingsdaten stammen aus `train.csv`.
- Enthalten sind u. a. folgende Features:
  - Kilometerstand
  - Baujahr / Alter des Autos
  - Leistung (PS, Drehmoment)
  - Zustand & Bewertung
  - Wirtschaftlichkeit & Höchstgeschwindigkeit

##  Modell
- Implementiert mit **TensorFlow/Keras**.  
- Enthält Normalization-Layer und Dense-Layer.  
- Optimierung mit **Adam**, Loss = **MeanSquaredError**, Metrik = **RootMeanSquaredError**.  

##  Ergebnisse
- Training Loss sinkt stetig → das Modell lernt.  
- Validation Loss bleibt relativ hoch → Hinweis auf Overfitting.  
- Das Modell kann Grundmuster erkennen, aber braucht bessere Features / Regularisierung.  

##  Nächste Schritte
- Feature Engineering (z. B. neue Variablen aus den vorhandenen Daten ableiten)  
- Regularisierung (Dropout, L2)  
- Hyperparameter-Tuning (Batchgröße, Lernrate, Layeranzahl)  
- Größeren oder vielfältigeren Datensatz nutzen  

##  Anforderungen
- Python 3.9+
- TensorFlow
- Pandas, Numpy, Matplotlib, Seaborn

## 📜 Lizenz
Dieses Projekt ist nur zu Lernzwecken gedacht. Keine kommerzielle Nutzung.
