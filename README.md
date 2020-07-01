# The-Planning-Board-fullApp

## Развертывание:

#### Создание виртуальной среды:
```
python -m venv venv
```
---
#### Активация виртуальной среды:
```
venv\Scripts\activate.bat
```
---
#### Установка зависимостей:
```
pip install -r req.txt
```
---
#### Развертывание клиента
```
cd client
npm i
npm run build
```
---
#### Миграции
```
python manage.py makemigrations
python manage.py migrate
```
---
#### Запуск
```
python manage.py runserver
```
