# Задания: работа со списками в Python

## Задание 1: Фильтрация положительных чисел

**Условие:**  
Напишите программу, которая:
1. Принимает список чисел, разделенных пробелами
2. Создает новый список, содержащий только положительные числа из исходного списка
3. Выводит отфильтрованный список

**Требования:**
- Обработать случай, когда ввод содержит нечисловые значения
- Вывести количество отфильтрованных элементов

**Пример работы:**
```
Введите числа через пробел: 5 -3 2.5 0 10 -7.2
Положительные числа: [5, 2.5, 10]
Найдено 3 положительных числа
```
==================================
## Задание 2: Обработка списка строк

**Условие:**  
Напишите программу, которая:
1. Принимает список слов через пробел
2. Создает:
   - Список длин каждого слова
   - Список слов в верхнем регистре
   - Список слов, начинающихся на гласную букву
3. Выводит все полученные списки

**Требования:**
- Учитывать русские и английские гласные
- Обрабатывать пустой ввод

**Пример работы:**
```
Введите слова через пробел: яблоко Joy ананас tree
Длины слов: [6, 5, 3, 4]
Верхний регистр: ['ЯБЛОКО', 'JOY', 'АНАНАС', 'TREE']
Слова на гласную: ['яблоко', 'ананас', 'tree']
```
