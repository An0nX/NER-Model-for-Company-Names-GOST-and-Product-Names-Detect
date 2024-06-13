# NER Model for Company Names, GOST, and Product Names Detection
![image](https://github.com/An0nX/NER-Model-for-Company-Names-GOST-and-Product-Names-Detect/assets/80145620/eb7fa309-d4d9-4c7b-a6e9-7bbdb5f0e3b8)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![spaCy](https://img.shields.io/badge/spaCy-3.0+-brightgreen)
![License](https://img.shields.io/badge/License-GPLv3-lightgrey)
![Issues](https://img.shields.io/github/issues/An0nX/NER-Model-for-Company-Names-GOST-and-Product-Names-Detect)

### Особенности

- **Определение названий компаний**
- **Определение стандартов ГОСТ**
- **Определение названий товаров**
- **Поддержка русского языка**

### Установка

1. Клонируйте репозиторий:
    ```sh
    git clone https://github.com/An0nX/NER-Model-for-Company-Names-GOST-and-Product-Names-Detect.git
    ```

2. Установите зависимости:
    ```sh
    pip install -r requirements.txt
    ```

### Использование

Для загрузки и использования модели, выполните следующий код:

```python
import spacy
nlp = spacy.load("path_to_your_model")

# Пример использования
doc = nlp("Ваш текст для обработки")
for ent in doc.ents:
    print(ent.text, ent.label_)
```
