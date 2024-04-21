### Код скрипта ТЗ номер 1 

Ниже представлено обьяснение моего скрипта 


Этот Bash-скрипт предназначен для копирования всех файлов из одной директории (входной директории) в другую (выходную директорию), при этом предотвращая перезапись файлов с одинаковыми именами.
Скрипт проверяет, передано ли ровно два аргумента (имена входной и выходной директорий). Если нет, выводится сообщение о неправильном использовании скрипта, и скрипт завершает выполнение с ошибкой. С помощью команды find, скрипт ищет все файлы в директории, выводя результаты с разделителем, что позволяет корректно обрабатывать имена с пробелами и специальными символами. Цикл while считывает эти имена файлов для последующей обработки. Из полного пути файла извлекается только имя файла, и формируется путь к целевому файлу в выходной директории. Если файл с таким именем уже существует в выходной директории, к имени файла добавляется счетчик, чтобы избежать перезаписи.


### Для запуска 

```
sh tz1PostniiIurii233.sh <входная директория> <Выходная директория>
```
