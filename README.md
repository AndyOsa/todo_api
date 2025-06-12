TO-DO List API

Цей проєкт — RESTful API для керування списком завдань, створений за допомогою Django REST Framework.

Можливості

- Створення завдань (POST /tasks)
- Перегляд списку завдань з фільтрацією за статусом або дедлайном (GET /tasks)
- Оновлення завдань (PUT /tasks/{id})
- Видалення завдань (DELETE /tasks/{id})

Встановлення


```bash
git clone https://github.com/AndyOsa/todo_api.git
cd todo_api
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
