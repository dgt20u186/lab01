# lab01
## Далгатов Гитиномагомед, группа ИУ8-22
1. Скачайте библиотеку *boost* с помощью утилиты **wget**. Адрес для скачивания https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz.

   ...Команда: ```$ wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz```

   ...Вывод:
```
--2021-02-28 14:29:12--  https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
Распознаётся sourceforge.net (sourceforge.net)… 216.105.38.13
Подключение к sourceforge.net (sourceforge.net)|216.105.38.13|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 301 Moved Permanently
Адрес: https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/ [переход]
--2021-02-28 14:29:13--  https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/
Повторное использование соединения с sourceforge.net:443.
HTTP-запрос отправлен. Ожидание ответа… 302 Found
Адрес: https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/download [переход]
--2021-02-28 14:29:13--  https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/download
Повторное использование соединения с sourceforge.net:443.
HTTP-запрос отправлен. Ожидание ответа… 302 Found
Адрес: https://downloads.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz?r=&ts=1614511753&use_mirror=jztkft [переход]
--2021-02-28 14:29:13--  https://downloads.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz?r=&ts=1614511753&use_mirror=jztkft
Распознаётся downloads.sourceforge.net (downloads.sourceforge.net)… 216.105.38.13
Подключение к downloads.sourceforge.net (downloads.sourceforge.net)|216.105.38.13|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 302 Found
Адрес: https://jztkft.dl.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz [переход]
--2021-02-28 14:29:14--  https://jztkft.dl.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz
Распознаётся jztkft.dl.sourceforge.net (jztkft.dl.sourceforge.net)… 45.67.159.245
Подключение к jztkft.dl.sourceforge.net (jztkft.dl.sourceforge.net)|45.67.159.245|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 111710205 (107M) [application/x-gzip]
Сохранение в: «boost_1_69_0.tar.gz.1»

boost_1_69_0.tar.gz 100%[===================>] 106,53M  1,31MB/s    за 57s     

2021-02-28 14:30:12 (1,85 MB/s) - «boost_1_69_0.tar.gz.1» сохранён [111710205/111710205]
```
2. Разархивируйте скаченный файл в директорию ~/boost_1_69_0.

...Команда: ```$ tar -xf boost_1_69_0.tar.gz```.
3. Подсчитайте количество файлов в директории ~/boost_1_69_0 не включая вложенные директории.

...Команда: ```$ ls -l | wc```

...Вывод:
```     19     164    1211```
Поскольку ls выводит размер всех файлов в папке строкой total, то у нас 18 файлов.

...Кол-во файлов: 18.
4. Подсчитайте количество файлов в директории ~/boost_1_69_0 не включая вложенные директории.

...Кол-во файлов: 12.
5. Подсчитайте количество заголовочных файлов, файлов с расширением .cpp, сколько остальных файлов (не заголовочных и не .cpp).

...Команда 1: ```$ find . -type f -name "*.h" | wc -l```

...Вывод: 296

...Команда 2: ```find . -type f -name "*.cpp" | wc -l```

...Вывод: 13774.
6. Найдите полный пусть до файла ```any.hpp``` внутри библиотеки *boost*.
 
...Команда: ```$ ls any.hpp```
   
...Вывод: ```any.hpp```
7. Выведите в консоль все файлы, где упоминается последовательность ```boost::asio```.

...Команда: 
