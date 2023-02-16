# Django Blog
Приложение для ведения блога, созданное с помощью Django framework.
## Характеристики
1. Регистрация пользователя
2. Создание, чтение, изменение и удаление постов в блоге
3. Отображание записей в блоге в виде списка с разбивкой по страницам
4. Поиск постов по имени автора или названия
5. Добавление и удаление комментариев к постам
## Загрузка
1. Скопируйте репозиторий
```python
git clone https://github.com/katyasobol/django-blog.git
```
2. Создайте виртуальную среду
```python
python3 -m venv env
```
3. Активируйте виртуальную среду
```python
source env/bin/activate
```
4. Установите все зависимости
```python
pip install -r requirements.txt
```
5. Запустите миграции
```python
python manage.py migrate
```
6. Создайте суперюзера
```python
python manage.py createsuperuser
```
7. Запустите приложение
```python
python manage.py runserver
```
