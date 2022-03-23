<h3>Tasks</h3>

Создать веб-сервис, который будет выводить "Rekruto! Давай дружить!". 
URL с GET запросом, который будет выводиться уже на странице:

url должен быть таким
```
xx.xx.xx.xx./?name=Rekruto&message=Давай дружить!
```
и выводилось на странице
```
Hello {name}! {message}!
```

<h3>Инструкция по запуску:</h3>

1. Клонирование проекта
```
git clone git@github.com:kiri3914/FastAPI-Test.git
```
2. Создание вертульного окружения

```
virtualenv venv
```

3. Активация вертульного окружения
```
source env/bin/activate
```
4. Установка зависимостей

```
pip install -r requirements.txt
```
5. Запуск
```
uvicorn index:app --reload
```
