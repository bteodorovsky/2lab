# Звіт до роботи
## Тема: Основи програмування на Python
### Мета роботи: Вивчити основні конструкції в Python
---
### Виконання роботи
- Результати виконання завдання 1;
    i. Попракитикувався з простими змінними, списками list, наборами set та словниками dict:
    my_list = [1, 2, 3, 4, 5]
    print (my_list)
    my_set = {1, 2, 3}
    my_set.add(4)
    print(my_set)
    ii. Виведів вбудовані константи:
    print("Константа нуля:", 0)
    print("Константа значення True:", True)
    iii. Вивів результат роботи вбудованих функцій:
    lst = [1, 2, 3, 4, 5]
    print(len(lst))
    print(round(2.1941, 2)) 
    iv. Познайомився з циклами. Написав код який демонструє роботу циклів:
    for i in range(1, 5):
    print(i)
    fruits = ["apple", "banana", "cherry"]
    for fruit in fruits:
    print(fruit)
    v. Познайомився з розгалуженнями:
    num = -10
    if num > 0:
    print("Число є додатнім")
    elif num == 0:
    print("Число дорівнює нулю")
    else:
    print("Число є від'ємним")
    x = 5
    y = 10
    result = x < y
    print(result)
    vi. Написав свій варіант коду з помилкою:
    a = 10
    b = 0
    try:
    c = a / b
    print(c)
    except:
    print("Помилка: Ділення на нуль!")
    finally:
    print("Кінець програми")
    vii. Контекст-менеджер with:
    with open("file.txt", "w") as f:
    f.write("Hello, World!")
    viii. Познайомився з Python lambdas:
    square = lambda x: x**2
    print(square(5))

- вставлені рисунки (скріншоти екрана або фотографії виконаного завдання у зошиті);

![alt text](https://github.com/BobasB/it_college/raw/main/reports/pictures/logo-lit.jpg "ІТ Коледж")

- вставлений код / текстовий або числовий результат / інші результати:
Результати:
i.
[1, 2, 3, 4, 5]
{1, 2, 3, 4}
ii.
Константа нуля: 0
Константа значення True: True
iii.
5
2.19
iv.
1
2
3
4
apple
banana
cherry
v.
Число є від'ємним
True
vi.
Помилка: Ділення на нуль!
Кінець програми
vii.
viii.
25
### Висновок: Завдяки цій програмі я оволодів основами програмування на Python