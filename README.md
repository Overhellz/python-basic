# python-basic

https://github.com/Overhellz/python-basic

---

https://stepik.org/course/58852/promo

---

### Ввод-вывод данных, переменные

#### print

```python
# примеры использования print
print('Мы изучаем язык Python')
print('Я', 'учусь', 'программировать', 'на', 'Python!')
print()
print('1', '2', '4', '8', '16')

print('В тексте есть "двойные" кавычки')
print("В тексте есть 'одинарные' кавычки")
print("I'm", 'the', "BAD", 'guy')
```

#### input

```python
# примеры использования input
print('Как тебя зовут?')  # вывод текста
print('Привет,', input())  # ввод текста и вывод текста

# сразу выводим текст и присваиваем значение переменной
name = input('Как тебя зовут?')

first = input()
second = input()

print('I am', first, 'and', second)
```

#### Переменные

Для именования переменных принято использовать стиль **lower_case_with_underscores** (слова из маленьких букв с
подчеркиваниями)

```python
# примеры работы с переменными
city = 'Тула'
print(city, '- мой город!')
# >>> Тула - мой город!

name = 'Алеша'
city = 'Тула'
print('Меня зовут', name, '.', city, '- мой город!')
# >>> Меня зовут Алеша . Тула - мой город!
```

#### sep, end, PEP 8

```python
# примеры работы с sep и end
print('aa', 'bb', 'cc')
print('aa', 'bb', 'cc', sep=' ', end='\n')
print('a', 'b', 'c', sep='', end='')
```

#### множественное присваивание

```python
# примеры работы с множественным присваиванием
name, surname = 'Timur', 'Guev'
print('Имя:', name, 'Фамилия:', surname)

name, surname = input(), input()
print('Имя:', name, 'Фамилия:', surname)
```

```python
# пример обмена значений двух переменных
name1 = 'Timur'
name2 = 'Gvido'

name1, name2 = name2, name1
```

```python
# в качестве названия переменных запрещено использовать ключевые (зарезервированные) слова:
False
True
None
and
with
    as
assert
break


class


    continue


def


    del
elif
else
except
finally
try
    for
    from

global
if
    import
in
is
lambda
        nonlocal
        not
        or
        pass
        raise
        return
        while
        yield
```

#### PEP 8

При оформлении программ мы будем пользоваться PEP 8 — Python Enhancement Proposal. Этот документ предлагает единый и
общепринятый стиль написания программ на языке Python. Документ создан по рекомендациям Гвидо Ван Россума, автора
Python.

#### Однострочные комментарии

```python
# Это комментарий в программе на языке Python.
print('Python rocks!')
```

#### Комментарий в конце строки

```python
print('Python rocks!')  # Это комментарий в программе на языке Python.
```


