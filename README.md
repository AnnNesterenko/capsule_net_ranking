# capsule_net_ranking

Репозиторий содержит имплементацию капсульной нейронной сети для ранжирования текстовых документов по семантической схожести, код построение эмбеддингов, а также результаты сравнения капсульной сети с классическим подходом. 

Навигация по репозиторию:
### CapsE
имплементация архитектуры сети, капсульного слоя, процесса динамической марштрутизации и обучения, предобработка данных

### embeddings_prepare
код построения векторных представлений текстов - Doc2Vec, FastText, BERT

### research
процесс обучения моделей, визуализация результатов, реализация косинусной меры схожести текстов

### data
в данном разделе хранится все, что касается используюемых наборов данных - MIND и arXiv triplets. Также содержит код выгрузки текстов статей по url-адресам

### main articles
все основные научные статьи, используемые в работе, в формате pdf
