# pg_export
postgresql linux bash export and import utility database to file with tables sells greater than 1 gb

If even one of your database table became greater than 1gb pg_dump and pg_dumpall utility is broken and save only a part of database into file. 
This utitlity is made to save separatly every table to distent file in bynary format and compress all files to one.
After exporting all tables this utility adds pg_import file to make import of copy more comfortable.

Это утилиты для импорта и экспорта баз данных в формате binary где есть ячейки таблицы размером больше 1 Гигабайта
Чаще всего такая проблема возникает с базами 1С, там запись в которой хранится описатель метаданных легко вырастает больше 1 гб.

Если одна из записей таблицы базы разрастается больше 1 гигабайта то утилиты pg_dump и pg_dumpall выгружают базу в файл частично, не целиком.

Данна утилита создана для выгрузки каждой таблицы отдельно в бинарном формате в файл.
После выгрузки всех таблиц к архиву добавляется файл pg_import для загрузки базы
