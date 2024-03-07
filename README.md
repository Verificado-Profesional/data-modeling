# data-modeling
Modelos de clasificación de noticias Falsas en Español como trabajo final de grado de la carrera Ingeniería Informática de la UBA.

## Targets 
### Resultados obtenidos para la clasificación de Noticias Falsas en Español
Paper |   Accuracy
------ |  -------------
Modelo para la detección de noticias falsas en formato texto en la red social Twitter | _82,7%_
Detection of Fake News in a New Corpus for the Spanish Language (Posadas Duran) | _77,3%_
Detecting Fake News Spreaders on Twitter from a Multilingual Perspective. | _78%_
RoBERTa large fake news detection spanish. | _77%_

- Estudios muestran que la acuraccy humana esta entre: 60 y 70 %
- Apuntaria a 90

## Resultados
### Métricas de nuestros modelos

#### Dataset en Español
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall
------ |  -------------|  ------|  ------|  ------|  ------
_Red Neuronal sin Vectorización_ | _42,5%_ |  |  |  
_Red Neuronal con Vectorización_ | _51,7%_ |  |  |  
_Small Bert Inglés_ | _81,6%_ |  |  |  
_Small Bert Subsampled_ | _79,2%_ |  |  |  
_Spacy Bert Spanish_ | _92.835%_ |  | _79.83%_ |  _84.14%_|  _78.925%_ 

#### Dataset de Chequeado
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall |   ROC AUC
------ |  -------------|  ------|  ------|  ------|  ------  |  ------  
_Small Bert Inglés_ | _69.14%_ | 1.4007|  _46.36%_ | _53.85%_ |  _40.70%_
_Spacy Bert Español_ | _82.44%_ | |  _66.40%_ | _66.40%_ |  _68.44%_

#### Dataset Combinado
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall |   ROC AUC
------ |  -------------|  ------|  ------|  ------|  ------  |  ------  
_Small Bert Inglés_ | _81.08%_ | 0.41 | _84.76%_| _78.80%_ | _91.71%_ 
_Spacy Bert Español_ | _82.44%_ | |  _66.40%_ | _66.40%_ |  _68.44%_
