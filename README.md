# Git Course  

<a id="ancor"></a>

### Списки

* Текст
* Текст
  * Вложенный текст
  * Еще один вложенный текст

1. Линия-разделитель 1 (***)
1. Линия-разделитель 2 (___)
1. Линия-разделитель 3 (---)

*** 
__Жирный текст__

***

_Курсивный текст_

*** 

___Жирный курсивный текст___

***

### Выделение объекта 

~~~

My Code 
Границы выделенной области: ' ~ ' * 3

~~~

### Цитаты
> Цитата
  >> Вложенная цитата

### Ссылка

[Сайт "Хабр"](https://habr.com/)  

***

### Сноски

Сноска первая [^1] и вторая [^2]
[^1]: Текст первой сноски
[^2]: Текст второй сноски

### Вставка картинок

![Просто картинка](images/logo.jpg)

[![Картинка со ссылкой](images/logo.jpg)](https://habr.com/)


***

### Таблицы

| Color | Quantity | Size |
:-------|:--------:|------:
Красный | 1 | 256
Синий | 2 | 22
Зеленый | 5 | 6489

***
\# Отображение спецсимволов через экранирование

***
### Список определений

Термин 1
: Определение

Термин 2
: Определение

***
### Внутренние ссылки
Можно сделать оглавление

[Вверх](#ancor)


***
### Alias

~~~
Path: Users / MyName / .gitconfig
[alias]
  s = status --short
  l = log --oneline --graph --decorate --all

  and more..
~~~

***
### Отмена команд

Указываем файл для отмены изменений (если отмена в одном файле)
~~~
git checkout -- index.html
~~~

Удаляем изменения во всех файлах
~~~
git checkout .
~~~

Если изменения добавлены командой 'add .' в одном конкретном файле
~~~
git reset index.html
git checkout -- index.html
~~~

Аналогично с группой файлов
~~~
git reset . 
git checkout .
~~~


