#  Описание проекта "Effective_Mobile_Junior_Python" 
Python 3.10

# Создание проекта
django-admin startproject project .
pip install django
python manage.py startapp ads

# Установка виртуального окружения
pip install -r requirements.txt
pip freeze > requirements.txt

# Создание миграций
python manage.py makemigrations --merge
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
python -m unittest ads.tests.py
python -m unittest discover
$ ./manage.py test   

pytest

https://yandex.ru/video/preview/13194727536262874304


# Начальная страница
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/1.png)
# Регистрация
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/2.png)
# Приветствие на домашней странице
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/3.png)
# Добавление объявления
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/4.png)
# Отображение добавленного объявления с возможностью его редактирования и удаления
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/5.png)
# Отображение добавленного объявления в списке с общими объявлениями, установлена пагинация
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/6.png)
# Поиск объявления по частичному совпадению в описании и оглавлении
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/7.png)
# Результаты поиска по частичному описанию.
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/8.png)
# Опубликовываем предложение по обмену
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/9.png)
# Вывод списка предложений по обмену
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/10.png)
# Редактирование статуса предложения по обмену
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/11.png)
# Вывод списка предложений по обмену
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/12.png)
# Панель администратора
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/13.png)
# Панель администратора. Добавление обявления.
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/14.png)
# Панель администратора. Добавленеи предложения
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/15.png)
# Панель администратора. Пользователи
![Uploading 1.png…](https://github.com/SergeyTsVL/Effective_Mobile_Junior_Python/blob/main/images/16.png)


<!--                <div class="video-item">-->
<!--                    <h3>{{ ad.title_video }}</h3>-->
<!--                    <video width="320" controls>-->
<!--                        <source src="{{ ad.video_file.url }}" type="video/mp4">-->
<!--                        Ваш браузер не поддерживает тег video.-->
<!--                    </video>-->
<!--                </div>-->
