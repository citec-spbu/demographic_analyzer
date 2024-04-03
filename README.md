# demographic_analyzer
Сервис по анализу мировых демографических процессов
# [Backend](https://github.com/web-ds-demographic/demographic-analyzer-back)
## Технологии и инструменты
- Python (Бэкенд)
- Django
## Как запустить 

#### Клонировать репозиторий

```
git clone git@github.com:web-ds-demographic/demographic-analyzer-back.git
```

#### Установить зависимости для бэкэнд-приложения Django

```
python3 -m venv venv
```

```
source/bin/activate/
```

```
pip install -r requirements.txt
```

```
python3 manage.py migrate
```

# [Frontend](https://github.com/st1gmat/demographic-analyzer-front)

## Технологии и инструменты

- Python
- Streamlit

## Как запустить 

#### Клонировать репозиторий

```
git clone git@github.com:web-ds-demographic/demographic-analyzer-front.git
```
#### Установить зависимости для фронтенд-приложения

```
python3 -m venv venv
```

```
source/bin/activate/
```

```
pip install -r requirements.txt
```

#### Перейти в директорию со страницами интерфейса
```
cd src
```
#### Запустить главный файл
```
streamlit run Home.py
```
