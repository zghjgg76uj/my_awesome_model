# my_awesome_model
Требования для работы проекта:


```Python 3.9+```


```Transformers```


Команда для установки зависимостей:


```pip install transformers```


Пример использования модели:

```
from transformers import pipeline
text = 'тест'
classifier = pipeline("text-classification", model="path_to/my_awesome_model/")
classifier(text) 

