# Modelo de Analisis de Sentimientos
Resultados de los diversos modelos de clasificación de sentimientos en español entrenados evaluando distintas metricas.

## Targets 
### Resultados obtenidos por trabajos similares para la clasificación de sentimientos en español

#### Clasificación Binaria: [Negativo - Positivo]
Paper | Accuracy  |   F1  |   Precision  |   Recall  | Data Size
------ |  -------------|  ------|  ------|  ------ |  ------
 Análisis de Sentimientos Aplicados a Opiniones en Español (Naïve Bayes)| _80.0 %_  | _81.0%_ |   _80.0%_ | _81.0%_ | 52.309
 Análisis de Sentimientos Aplicados a Opinione en Español (BERT (BETO))| _83.0 %_  | _88.0%_ |   _85.0%_ | _91.0%_ | 52.309
 A Spanish dataset for Targeted Sentiment Analysis of political headlines| _75.3%_  | _75.3%_ |    | | 2.438
 Analisis de Sentimientos de Tweets en Español (SDG)| _75.94 %_  | _75.06%_ |   _76.53%_ | _74.51%_ | 9.476
 Analisis de Sentimientos de Tweets en Español (XGBoost)| _74.41 %_  | _74.08%_ |   _74.92%_ | _73.26%_ | 9.476
 Análisis de sentimiento de comentarios en Play Store (BERT)| _81,00%_  | _80,00%_ | _81,00%_  | _81,00%_| 15.985

   

#### Clasificación Multiclase: [Negativo - Neutral - Positivo]
Paper | Accuracy  |   F1  |   Precision  |   Recall  | Data Size
------ |  -------------|  ------|  ------|  ------ |  -------
 Analisis de Sentimientos de Tweets en Español (SDG)| _75.94 %_  | _75.06%_ |   _76.53%_ | _74.51%_ | 9.476
 Analisis de Sentimientos de Tweets en Español (XGBoost)| _74.41 %_  | _74.08%_ |   _74.92%_ | _73.26%_ | 9.476
 Comparacion de analisis de sentimientos en comunidades de habla hispana| _66,64% %_  |  |   | | 9.476
 
### Capacidad de deteccion de sentimientos en personas
* Human Accuracy :  80-85%

## Resultados
### Métricas de nuestros modelos

#### Clasificación Binaria: [Negativo - Positivo]
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall
------ |  -------------|  ------|  ------|  ------|  ------
_RNN TF_ | _77,07%_ | 0.5227 | _77%_ |   _77%_ | _77%_
_Bert Base Uncased_ | _78.53%_ | - | _78.52%_ |   _78.67%_ | _78.61%_
_Multilingual Bert Uncased_ | _82.58%_ | - | _82.58%_ |   _82.57%_ | _82.59%_
_Spanish Bert Uncased_ | _86.47%_ | - | _86.47%_ |   _86.46%_ | _86.51%_
_Spanish Bert Cased_ | _86.60%_ | - | _86.60%_ |   _86.59%_ | _86.62%_


#### Clasificación Multiclase: [Negativo - Neutral - Positivo]
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall |  
------ |  -------------|  ------|  ------|  ------|  ------ 
_RNN TF_ | _53.28%_ |  1.27 | _53%_| _53%_ | _53%_ 
_Spanish Bert Uncased_ | _64.97%_ | - | _65.24%_ |   _65.85%_ | _64.97%_
