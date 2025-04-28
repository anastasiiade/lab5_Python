**Решение:**
```python
# Получаем ввод от пользователя
input_str = input("Введите числа через пробел: ")

# Инициализируем списки
numbers = []
positive_numbers = []

try:
    # Преобразуем ввод в список чисел
    numbers = [float(num) for num in input_str.split()]
    
    # Фильтруем положительные числа
    positive_numbers = [num for num in numbers if num > 0]
    
    # Выводим результат
    print(f"Положительные числа: {positive_numbers}")
    print(f"Найдено {len(positive_numbers)} положительных числа")

except ValueError:
    print("Ошибка: вводите только числа, разделенные пробелами")
```

==================================

**Решение:**
```python
# Получаем ввод от пользователя
words = input("Введите слова через пробел: ").split()

# Инициализируем списки
lengths = []
uppercase = []
vowel_words = []
vowels = {'а', 'е', 'ё', 'и', 'о', 'у', 'ы', 'э', 'ю', 'я',
          'a', 'e', 'i', 'o', 'u'}

# Обрабатываем каждое слово
for word in words:
    # Список длин
    lengths.append(len(word))
    
    # Список в верхнем регистре
    uppercase.append(word.upper())
    
    # Слова на гласную
    if word[0].lower() in vowels:
        vowel_words.append(word)

# Выводим результаты
print(f"Длины слов: {lengths}")
print(f"Верхний регистр: {uppercase}")
print(f"Слова на гласную: {vowel_words}")
```
