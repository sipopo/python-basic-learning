# Маленькое интро
Разбираемся с типом строка

# Теория 
В языке `python` всё, что заключено в кавычки - то строка.
```python
>>> 'Это строка в одинарных кавычках'
'Это строка в одинарных кавычках'
>>> "А это в двойных"
'А это в двойных'
``` 

Что делать, если нужно в строке использовать кавычку? Всё просто - используйте другие кавычки.
```python
>>> 'Строка содержащая " - двойную кавычку '
'Строка содержащая " - двойную кавычку '

>>> "Строка содержащая ' - одинарную кавычку "
"Строка содержащая ' - одинарную кавычку "
```

Бывает, что необходимо описать длиное предложение - не писать же, всё это бесонечно в одной строке. Используйте backslash ```\```.
```python
>>> "Это очень \
... длиная предлинная \
... строка"
'Это очень длиная предлинная строка'
```
Заметили, разбитая строчка превратилась в одну?
Иногда нужно написать текст без магических преобразований - используйте тройные кавычки.
```python
>>> pushkin = """
... У лукоморья дуб зелёный;
... Златая цепь на дубе том:
... И днём и ночью кот учёный
... Всё ходит по цепи кругом;
... Идёт направо - песнь заводит,
... Налево - сказку говорит.
... """
>>>>>> print(pushkin)

У лукоморья дуб зелёный;
Златая цепь на дубе том:
И днём и ночью кот учёный
Всё ходит по цепи кругом;
Идёт направо - песнь заводит,
Налево - сказку говорит.

```


## Задание 
