# Inversi-n-en-medios-de-publicidad
Regresión lineal múltiple para predecir ventas a partir de la inversión en TV, radio y periódico

Se construyó una regresión lineal múltiple para predecir ventas a partir de la inversión en TV, radio y periódico (200 datos, 70% entrenamiento y 30% prueba). El periódico no fue significativo (p = 0.84) y se eliminó; el modelo final usa solo TV y Radio: Ventas ≈ 4.64 + 0.055·TV + 0.102·Radio. Ajustó muy bien (R² ≈ 0.90 en entrenamiento y 0.91 en prueba, RMSE = 1.54) y, para TV = 100 y Radio = 50, pronostica ~15.2 de ventas (intervalo del 90%: 12.3 a 18.1). Los residuos no son normales y hay indicios de heterocedasticidad, por lo que los intervalos deben tomarse con cautela.
