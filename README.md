# GB_PostgreSQL
GeekBrains. Базы данных. PostgreSQL.


1. Создать все необходимые внешние ключи в базе данных vk. В качестве отчёта сдать команды 
создания ключей в текстовом виде.

2. Построить диаграмму отношений БД vk, экспортировать ее в изображение и приложить в 
качестве отчёта.

3. Создать в таблице фотографий столбец metadata типа JSON и следующими ключами - id, url, 
size и заполнить его значениями соответствующих строк. В отчёт приложить команды 
ALTER TABLE и UPDATE.

4. В таблице сообществ создать столбец members типа массив. Для сообщества с id = 3 
поместить в ячейку members идентификаторы всех пользователей, являющихся членами данной 
группы. В отчёт приложить выполняемые команды.

5. Создать пользовательский составной тип данных contacts c полями phone и email. В таблице 
пользователей добавить столбец user_contacts типа contacts. Заполнить столбец значениями из 
соответствующих строк. Для пользователя с id = 21 изменить email в столбце user_contacts на 
test@somemail.ru. В отчёт приложить выполненные команды.