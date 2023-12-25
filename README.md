# Звіт до роботи
## Тема: _згідно теми_
### Мета роботи: _згідно теми_

---
### Виконання роботи
* Результати виконання завдання *1...N*;
    1. Розробили/Створили ...
    1. Програма вивела значення ...
    1. Отримано наступні результати ...
    1. Навчились ...
* вставлені рисунки (скріншоти екрана або фотографії виконаного завдання у зошиті);
    > якщо графічних файлів багато то краще помістити їх у  окрему папку, наприклад у мене це папка `pictures`. Уважно   дивіться коли вставляєте URL - файл має бути представленим    як `raw`. А краще користуйтесь локальними шляхами!

* з використанням URL ![alt text](https://github.com/BobasB/it_college/raw/main/reports/pictures/logo-lit.jpg "ІТ Коледж")
    
* через локальні шляхи ![alt text](./pictures/logo-lit.jpg "ІТ Коледж")

pip install numpy

# Функція для виконання домашнього завдання (визначте її за необхідності)
def homework(task):
    print(task)
    # Тут ви можете виконати додаткові дії для кожного завдання

# Ваш початковий код
start = 5
size_of_vec = 100
x = range(size_of_vec)
a = np.arange(size_of_vec)
print(f"Масив згенерований простим range: {x[0:5]} та методом arange: {a[0:5]}")

a = np.arange(start, size_of_vec)
print(f"Можемо задавати початок генерації вектора, перший елемент: {a[0]}")

x = range(start, size_of_vec)
print("Те саме але з вбудованою функцією range:", x)
print("Власне вивід значень:", list(x)[0])

# дробові числа
x = np.arange(10.4)
print("Будемо мати:", x)
# крок
x = np.arange(0.5, 4, 0.5)
print("З кроком 0.5:", x)
# Заокруглення
x = np.arange(0.04, 1.84, 0.08)
print("З кроком 0.08:", x, "\n Зверніть увагу на заокруглення")

y = x * 2.5
print("Після перемноження:", y)

%pip install numpy
def homework(message):
    print("\n>>>>>", message, "\n")
import numpy as np
temperature = [20.1, 20.1, 20.2, 20.4]
print(temperature)

t1 = temperature * 5

print(f"При множенні на 5 маємо: {t1}")

t1 = [ x*5 for x in temperature] 
print(f"Тепер отримаємо: {t1}") 

t2 = np.array(temperature)
print("Масив з використанням методів NumPy", t2)

t3 = t2 * 5
print("При множенні на 5 отримуємо:", t3)

A = np.array([ [3.4, 8.7, 9.9], 
               [1.1, -7.8, -0.7],
               [4.1, 12.3, 4.8],
               [7.0, -3.9, 5.1]])

print(f"""Масив:
{A}
Виміри: {A.shape}
Принцип номерації такий самий, ТІЛЬКИ:
Якщо задати одне значення то візьметься цілий рядок:
    Перший рядок: {A[0]}
    Останній рядок: {A[-1]}
Для того щоб взяти цілий стовпець (символ : вказує взяти всі елементи): 
    Перший стовпець: {A[:,0]}
    Останній стовпець: {A[:,-1]}
Потрібно задавати два значення для отримання конкретного елемента: 
    Перший елемент: {A[0][0]} або {A[0, 0]}
    Останній елемент: {A[3][2]} або {A[-1][-1]} або {A[3, -1]}
""")

homework("Попрактикуйтесь в доступі до багатовимірного масиву, виведіть елементів які належать діагоналі.")
---
### Висновок:
> у висновку потрібно відповісти на запитання:

- :question: Що зроблено в роботі;
- Виведення інформації про створені масиви,Виведення елементів масиву зі зміщенням
- :question: Чи досягнуто мети роботи;
- Так
- :question: Які нові знання отримано;
- Виведення інформації про створені масиви,Виведення елементів масиву зі зміщенням
- :question: Чи вдалося виконати всі завдання;
- Так
- :question: Чи виникли складності у виконанні завдання;
- Ні
- :question: Чи подобається такий формат здачі роботи (Feedback);
- Так
- :question: Побажання для покращення (Suggestions);
- Немає
