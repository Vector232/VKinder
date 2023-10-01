# VKINDER - 'Я таки найду тебе пару!'
Маленький сервис для поиска пользователя ВК.

## Чтобы работало:
1. Python 3.11 и выше.
2. Нужен файл .env с содержимым по шаблону:
---- 
- CLIENT_ID = '51******77'
- dialect = 'postgresql'
- driver = 'psycopg2'
- login_DB = 'postgres'
- password_DB = '********'
- server_name = 'localhost'
- port = '5432'
- db_name = 'VKinderDB'
  
  *Возможны различия. Необходимо проконсультироваться с сисадмином.
----
3. Нужна БД с соответствующим именем. Пустой достаточно. Все создаст скрипт. И удалит.
4. pip install -r requirements.txt
5. python -m VKinder

## Задачи
### Преимущества сервису:

1. Получать токен от пользователя с нужными правами.                (Готово!)
2. Программа декомпозирована на функции/классы/модули/пакеты.       (Готово!)
3. Результат программы записывать в БД.                             (Готово!)
4. Люди не должны повторяться при повторном поиске.                 (Готово!)
5. У программы должен быть свой отдельный репозиторий.              (Готово!)
6. Все зависимости должны быть указаны в файле requiremеnts.txt.    (Готово!)
7. В vk максимальная выдача при поиске 1000 человек. Подумать как это ограничение можно обойти. (Готово!)
8. Добавить возможность ставить лайк, выбранной фотографии. (50%)
9.  У каждого критерия поиска должны быть свои веса. То есть совпадение по возрасту должны быть важнее общих групп. Интересы по музыке важнее книг. Наличие общих друзей важнее возраста. И так далее. (Готово!)
10. Добавлять человека в избранный список, используя БД. (Готово!)
11. Добавлять человека в черный список чтобы он больше не попадался при поиске, используя БД. (Готово!)
12. К списку фотографий из аватарок добавлять список фотографий, где отмечен пользователь. (Готово!)

## Что я могу с этим делать?
1. Найти наиболее подходящие кандидатуры для создания совместного будущего.
2. Увидеть результаты поиска в текстовом виде.
3. Увидеть ссылки на самые популярные фото в профиле кандидатов(к).
4. Увидеть ссылки на фото, где отмечен кандидат(ка).
5. Поставить лайк понравившейся фотографии.
6. Добавить кандидата(ку) в список избранных, чтобы был(а) рядом.
7. Добавить кандидата(ку) в черный списокБ чтобы не мешал.


