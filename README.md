# GIT-3
Собираем файл из кусочков.

Считываем с консоли имена файлов.
Каждый файл имеет имя: [someName].partN.

Например, Lion.avi.part1, Lion.avi.part2, ..., Lion.avi.part37.

Имена файлов подаются в произвольном порядке. Ввод заканчивается словом "end".
В папке, где находятся все прочтенные файлы, создаем файл без суффикса [.partN].

Например, Lion.avi.

В него переписываем все байты из файлов-частей используя буфер.
Файлы переписываем в строгой последовательности, сначала первую часть, потом вторую, ..., в конце - последнюю.
Закрываем потоки.