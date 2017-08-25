# Hello
This is a simple README.md file for test project
```bash
    git config --global user.name "your_name"
    git config --global user.email "your_email"
    git config --global core.autocrlf true
    git config --global core.safecrlf true
    
    cd path/to/directory
    touch test.txt
    "Hello world!"
    
    git init
    git add test.txt
    git commit -m "First Commit"
    
    [master (root-commit) d227fd1] First Commit
     1 file changed, 1 insertion(+)
     create mode 100644 hello.html
    
    git remote add origin https://github.com/artembell/hello.git
    git push -u origin master
    
    Counting objects: 3, done.
    Writing objects: 100% (3/3), 223 bytes | 0 bytes/s, done.
    Total 3 (delta 0), reused 0 (delta 0)
    To https://github.com/artembell/hello.git
     * [new branch]      master -> master
    Branch master set up to track remote branch master from origin.
```
    

# h1 заголовок первого уровня

## h2 заголовок второго уровня

### h3 заголовок третьего уровня

#### h4 заголовок четвёртого уровня

##### h5 заголовок пятого уровня

###### h6 заголовок шестого уровня

[Мой сайт](http://webdesign.ru.net)

<http://webdesign.ru.net>

**Жирный шрифт**
***Наклонный жирный***

`выделенные слова`


    
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

```php
<?php here_pagecontent(); ?>
```

```scss /* или css */
@import "bower_components/tree-normalize/generic.normalize";
h1 {
 font-size:1.5em;
 font-weight: 300;
}
```

> Цитата
> > Вложенная цитата

> Продолжение цитаты

Название файла  | Содержание файла
----------------|----------------------
style.css       | Пустой файл каскадной таблицы стилей, в который производится сбока необходимых стилей
reset.css       | Reset CSS от Эрика Мейера
normalize.css   | Нормалайзер CSS от Nicolas Gallagher
block.css       | Основные стили блоков системы
addition.css    | Дополнительные стили
fontawesome.css | Стили иконочного шрифта
layout.css      | Основные стили, применительно к определённому сайту
lightbox.css    | Стили лайтбокса, если таковой используется
index.html      | Индексный файл для проверки вносимых изменений

* Пункт 1
* Пункт 2
* Пункт 3

1. Пункт 1
2. Пункт 2
3. Пункт 3

- ul
+ ul
  + ul - для вложенных списков нужно поставить 2 пробела
    + ul - третий уровень
      + ul - четвёртый уровень
        + ul - пятый и т.д.

_наклонный_ _шрифт_ _наклонный__шрифт_

![screenshot of sample](http://webdesign.ru.net/images/Heydon_min.jpg)
