# UIP3
Данный репозиторий создан для выполнения лабораторной работы №3 по дисциплине "Управление информационными проектами".


# Выполнение лабораторной (заголовок первого уровня)


## Списки (заголовок второго уровня)
Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные) списки. 
1.  пункт1
2.  пункт2
3.  пункт3

*  пункт1
*  пункт2
*  пункт3


## Цитаты (заголовок второго уровня)

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования


## Блоки кода (заголовок второго уровня)

Для создания блока кода в языке Markdown необходимо каждую строку параграфа начинать с отступа, состоящего из четырех пробелов или одного символа табуляции. Блок кода продолжается до тех пор, пока не встретится строка без отступа (или конец текста). 

  class Employee:  
    """Базовый класс для всех сотрудников"""  
    emp_count = 0  
  
    def __init__(self, name, salary):  
        self.name = name  
        self.salary = salary  
        Employee.emp_count += 1  
  
    def display_count(self):  
        print('Всего сотрудников: %d' % Employee.empCount)  
  
    def display_employee(self):  
        print('Имя: {}. Зарплата: {}'.format(self.name, self.salary))
        
        
## Горизонтальные линии (заголовок второго уровня)

Первая часть текста, который необходимо разделить
***
Вторая часть текста, который необходимо разделить

## Изображения (заголовок второго уровня)

![Альтернативный текст](https://anivisual.net/avatar/01/86/32217419.jpg)

## Связь с другим файлом (заголовок второго уровня)
[ссылка на other_file.md](other_file.md)
