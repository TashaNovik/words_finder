# words_finder
Мой алгоритм:
Алгоритм словами:
1.	Открыть файл словаря: Открыть текстовый файл (.txt), содержащий словарь Ожегова.
2.	Создать пустой список для результатов: Создаём пустой список, в котором будем хранить найденные слова.
3.	Читать файл построчно: Для каждой строки в файле выполняем следующие шаги:
o	Извлечь слово: Извлечь первое слово из строки (до запятой).
o	Проверить длину: Если длина слова меньше 6 букв, переходим к следующей строке.
o	Сравнить начало и конец: Если первые три буквы слова совпадают с последними тремя буквами, добавляем это слово в список результатов.
4.	Закрыть файл: После обработки всех строк закрываем файл словаря.
5.	Вернуть результат: Возвращаем список найденных слов.

Если брать чужогй алгоритм, то я выберу алгоритм Владислава:
1.   Открываем файл для чтения
1.1. Создаем множество для слов
1.2. Читаем файл построчно
1.3. Разбиваем текст на отдельные слова, используя пробелы, переносы строк и знаки препинания как разделители
1.4. Записываем слова в множество


2.   Обработка каждого слова
2.1. Пройтись по каждому слову во множестве
2.2. Проверить, что длина слова не меньше 6 символов
2.3. Извлечь три первых и три последних символа слова.
2.4. Сравнить извлеченные части. Если они совпадают, вывести слово на экран, а если таких слов нет, сообщить об этом пользователю.

Алгоритм Алексея
1. Открыть файл.

2. Записать содержимое файла в переменную.

3. Составить список слов, которые начинаются на 2 скрытых символа "новая строка" и заканчиваются запятой с количеством букв строго больше 5.

4. Создать пустой список words_list.

5. Создать цикл по списку слов.
5.1 Выбрать слово по порядку.
5.2 Сделать проверку "первые 3 буквы слова" = "последние 3 буквы слова".
	- если ложь, то ничего 
	- если правда, то добавляем слово в список

6. Сохранить список в файл words_list.csv.
