# D5.11
Module D5 homework


#### Список роутов:
+ admin/ - панель администратора;
+ books_table/ - таблица книг в билиотеке(можно проверить, одолжена ли книга кому-то);
+ books/ и authors/  - вывод всех книг и авторов библиотеки;
+ publishers/ - вывод списка издательств и их книг;
+ friends/ - вывод списка друзей и книг, которые они одолжили;
+ author/create_many и book/create_many - формсеты


#### Для проверки задания:
1. Стянуть репозиторий к себе:
```
    git clone https://github.com/eternityxxxx/D5.11.git
```
2. Установить зависимости из requirements.txt:
```
    pip install -r requirements.txt
```
3. Запустить сервер:
```
    cd 'my_library'
    python manage.py runserver
```
4. Перейти по данному урлу:
```
    friends/
```