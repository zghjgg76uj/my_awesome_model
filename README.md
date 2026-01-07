# my_awesome_model

Из-за ограничений GitHub полностью загрузить проект сюда не удалось, скачать его можно по ссылкe с Google Drive: https://drive.google.com/file/d/1mBm1luidJ5GBDrsecrP7PIu6yQovB2S3/view?usp=drive_link



Требования для работы проекта:


```Python 3.9+```


```Transformers```


```PyTorch```


Команда для установки зависимостей:


```pip install transformers```


```pip install torch```

Пример использования модели:

```
from transformers import pipeline
text = 'тест'
classifier = pipeline("text-classification", model="path_to/my_awesome_model/")
print(classifier(text)) 

