# Modelo de Analisis de Sentimientos
Resultados de los diversos modelos de clasificación de sentimientos en español entrenados evaluando distintas metricas.

## Targets 
### Resultados obtenidos por trabajos similares para la clasificación de sentimientos en español
Paper | Accuracy  |   F1  |   Precision  |   Recall
------ |  -------------|  ------|  ------|  ------
 Análisis de Sentimientos Aplicados en Español (Naïve Bayes)| _80.0 %_  | _81.0%_ |   _80.0%_ | _81.0%_
 Análisis de Sentimientos Aplicados en Español (BERT (BETO))| _83.0 %_  | _88.0%_ |   _85.0%_ | _91.0%_
 Análisis de sentimientos y emociones en redes sociales usando ML| _88.0 %_  | _88.0%_ |   _88.0%_ | _88.0%_
### Capacidad de deteccion de sentimientos en personas
* Human Accuracy :  80-85%

## Resultados
### Métricas de nuestros modelos

#### Clasificación Binaria: [Negativo - Positivo]
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall
------ |  -------------|  ------|  ------|  ------|  ------
_RNN TF_ | _77,07%_ | 0.5227 | _77%_ |   _77%_ | _77%_
_Spanish Bert Uncased_ | _85.50%_ | - | _85.49%_ |   _85.50%_ | _85.52%_

#### Clasificación Multiclase: [Negativo - Neutral - Positivo]
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall |  
------ |  -------------|  ------|  ------|  ------|  ------ 
_RNN TF_ | _53.28%_ |  1.27 | _53%_| _53%_ | _53%_ 
_Spanish Bert Uncased_ | _64.97%_ | - | _65.85 %_ |   _85.50%_ | _64.97%_
