# Test File 
## In Markdown

You can use _Markdown_ and _reStructuredText_ in the same Sphinx project. We support this natively on Read the Docs, and you can do it locally:

``$ pip install recommonmark``

Then in your ``conf.py:``

``from recommonmark.parser import CommonMarkParser``

``source_parsers = {``
    ``'.md': CommonMarkParser,``
``}``

``source_suffix = ['.rst', '.md']``
# Note 
![Note mark](https://github.com/MaslovaEV/test/blob/master/icon48.png?raw=true)

Markdown doesn't support a lot of the features of Sphinx, 
           like inline markup and directives. However, it works for 
           basic prose content. reStructuredText is the preferred 
           format for technical documentation, please read `this blog post`_ 
           for motivation.
           
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
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
