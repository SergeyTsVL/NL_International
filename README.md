#  Тестовое задание "ООО НЛ Континент" 


# Установка виртуального окружения
pip install -r requirements.txt
pip freeze > requirements.txt

# Создание миграций
python manage.py makemigrations
python manage.py migrate

# Запуск приложения 
python manage.py runserver

# Создание учетной записи администратора
python manage.py createsuperuser
Username (leave blank to use 'tsars'): tsars
Email address: test@example.com
Password: 123456789


# Запуск всех тестов
python manage.py test NL_International


# Начальная страница
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/1.png)
# Регистрация
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/2.png)
# Приветствие на домашней странице
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/3.png)
# Добавление объявления
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/4.png)
# Отображение добавленного объявления с возможностью его редактирования и удаления
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/5.png)
# Отображение добавленного объявления в списке с общими объявлениями, установлена пагинация
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/6.png)
# Поиск объявления по частичному совпадению в описании и оглавлении
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/7.png)

