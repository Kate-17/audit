# Инспекции/аудит кода

https://github.com/ameyyadav09/GraphAlgos/tree/master/AllpairShortestPath


| Место ошибки | Суть ошибки | Рекомендации по устранению |
| ------------- |:-------------| :-----|
|AllPair_Johnson.java : 3  | Нарушение соглашения об именовании  | Использование в наименовании класса CamelCase #AllPairJohnson |
|  AllPair_Johnson.java : 28, AllPair_Johnson.java : 77 | Нарушение соглашения об именовании  | Использование в наименовании методов и функций camelCase #johnsonBell |
|  AllPair_Johnson.java : 11, AllPair_Johnson.java : 128,  AllPair_Johnson.java : 130| Нарушение соглашения об именовании  | Использование в наименовании переменных и массивов camelCase #numberOfVertices #nodeArray |
| AllPair_Johnson.java : 30, AllPair_Johnson.java : 31, AllPair_Johnson.java : 148, AllPair_Johnson.java : 98, AllPair_Johnson.java : 148 | Многократное использование "одного числа"   | Занесение этого числа в переменную #static int INF=999;  |
| AllPair_Johnson.java : 33  | Ненужное присваивание | Удаление |
| AllPair_Johnson.java : 38, AllPair_Johnson.java : 39 | Многократное вычисление | Занесение вычисления в переменную |
| AllPair_Johnson.java : 35,36,37,38, AllPair_Johnson.java : 45,46, AllPair_Johnson.java : 62,63, AllPair_Johnson.java : 79, AllPair_Johnson.java : 96,97,101, AllPair_Johnson.java : 111, AllPair_Johnson.java : 116,117, AllPair_Johnson.java : 133, AllPair_Johnson.java : 141, , AllPair_Johnson.java : 146,147| Излишнее использование фигурных скобок | Удаление |
| AllPair_Johnson.java : 128, AllPair_Johnson.java : 132, AllPair_Johnson.java : 140| Нет обработки исключения на неправильный ввод данных | Добавление обработок исключений |


Инспектор:
Мезенцева Екатерина
