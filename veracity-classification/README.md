# Modelo de Deteccion de Noticias Falsas
Resultados de los diversos modelos de clasificación de noticias falsas en español entrenados evaluando distintas metricas.

## Targets 
### Resultados obtenidos para la clasificación de Noticias Falsas en Español
Paper |   Accuracy
------ |  -------------
Modelo para la detección de noticias falsas en formato texto en la red social Twitter | _82,7%_
Detection of Fake News in a New Corpus for the Spanish Language (Posadas Duran) | _77,3%_
Detecting Fake News Spreaders on Twitter from a Multilingual Perspective. | _78%_
RoBERTa large fake news detection spanish. | _77%_
Humans and Algorithms Detecting Fake News [Human Accuracy] | _67%_


## Resultados
### Métricas de nuestros modelos

#### Dataset Combinado
Modelo |   Accuracy  |   Loss  |   F1  |   Precision  |   Recall |  
------ |  -------------|  ------|  ------|  ------|  ------ 
_Spacy Bert Español_ | __ | |  _66.40%_ | _66.40%_ |  _68.44%_
_Small Bert Inglés_ | _82.17%_ | 0.41 | _80.84%_| _84.57%_ | _80.05%_ 
_Multi Bert_ | _82.81%_ | | _81.61%_| _84.94_ | _80.82%_
_Spanish Bert_ | _83.17%_ | | _81.94%_| _85.62%_ | _81.10%_ 
_Spanish Bert Cased_ | _83.45%_ | | _82.23%_| _86.02%_ | _81.38%_ 
_Spanish + Sentiment_ | _83.74%_ | | _87.18%_| _79.80%_ | _96.06%_ 

