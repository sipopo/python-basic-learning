# Маленькое интро
* Разбираемся с функциями

# Теория
Начнем разбираться с функциями.
В `python` фукнции это куски кода, которые объеденены в блоки. 

Например, удобно выделить отдельный функционал в некий блок, а дальше вызывать его из любого места программы.
Программа становиться менее загромажденной и более "читабельной".

```python
def greet(name):
    """ Функция здоровается с тобой """
    print(f'Привет, не повторимый {name}')


# Текст основной программы

greet('Незнайка') # Пример вызова функции
greet('Пончик')
greet('Топтыга')
```

Теперь для того-чтобы поменять текст приветсвия достаточно изменить приветсвие в фукнции, что отразиться в каждом выводе.

Функция может возвращать значения, для этого используйте ключевое слово `return`
Например, напишем функцию возвращаемое максимальное число

```python
def return_max(a, b):
    """ Фозвращает максимально число издвух введенных """
    if a>b:
        return a
    else:
        return b

```


## Задание 
* Написать функцию, которая прощается с тобой 
* Написать функцию, которая возвращает сумму чисел
* Написать функцию, которая перемножает числа
