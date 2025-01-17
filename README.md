# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[4. Результат](.README.md#Результат)    
[5. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Этапы работы над проектом  
1. Инициализация переменных: создание переменных для подсчета количества попыток, хранения текущего предполагаемого числа и диапазона, где находится загаданное число.
2. Настройка цикла: определение условий цикла для продолжения угадывания числа.
3. Получение первого предполагаемого числа: задание переменной текущего предполагаемого числа равной 50 (середине диапазона от 1 до 100).
4. Уточнение предполагаемого числа: в зависимости от ответа об угадываемом числе, изменение текущего предполагаемого числа и его диапазона.
5. Увеличение количества попыток: каждый раз, когда программа делает новую попытку угадать число, увеличивается счетчик попыток.
6. Завершение программы: вывод результата - количество попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Создана программа, которая угадывает загаданное число от 1 до 100.
Реализован алгоритм, который позволяет угадывать число с минимальным количеством попыток. В среднем количество попыток равняется 4.
Код программы размещен в файле my_version_game

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Проект успешно реализован, и программа способна угадывать загаданное число с минимальным количеством попыток.
Работа над проектом была интересной и позволила поглубить знания в области алгоритмов и программирования.
:arrow_up:[к оглавлению](.README.md#Оглавление)
