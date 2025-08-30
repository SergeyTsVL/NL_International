#  Тестовое задание "ООО НЛ Континент" 


# Установка виртуального окружения
pip freeze > requirements.txt
pip install -r requirements.txt

# Создание миграций
python manage.py makemigrations
python manage.py migrate

# Запуск приложения 
python manage.py runserver

# Создание учетной записи администратора
python manage.py createsuperuser
Например:
Username (leave blank to use 'tsars'): tsars
Email address: test@example.com
Password: 123456789


# Запуск всех тестов
python manage.py test --keepdb
python manage.py test --verbosity 2


# Начальная страница
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/1.png)
# Добавление объявления с разными контентами: Картинки, видео, аудио
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/2.png)
# Поиск среди объявлений
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/3.png)
# Вывод результатов поиска
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/4.png)
# Пагинация, счетчик просмотров контента
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/5.png)
# inline-блоки
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/6.png)
# inline-блоки, с возможностью редактирования, добавления и удаления из панели администратора
![Uploading 1.png…](https://github.com/SergeyTsVL/NL_International/blob/main/images/7.png)

