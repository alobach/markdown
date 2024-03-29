# НАВИГАЦИЯ :octopus: with :heart:

1. [Заголовки](#Заголовки)

2. [Разделители](#Разделители)

3. [Текст](#Текст)

4. [Ссылки](#Ссылки)

5. [Таблица](#Таблица)

6. [Списки](#Списки)

7. [Изображение](#Изображение)

8. [Код](#Код)

# Заголовки

`````
# h1
## h2
### h3
#### h4
##### h5
###### h6
`````
# Разделители 
```
---
***
___
```

# Текст

**Жирный шрифт**

***Наклонный жирный***

`Выделенные слова`

~~Зачеркнутый текст~~

_Наклонный_ _шрифт_ _наклонный__шрифт_
```
**Жирный шрифт**

***Наклонный жирный***

`Выделенные слова`

~~Зачеркнутый текст~~

_Наклонный_ _шрифт_ _наклонный__шрифт_
```
> Цитата
> 
> Продолжение текста выделенного блока
>
> Завершение текста
```
> Цитата
> 
> Продолжение текста выделенного блока
>
> Завершение текста
```
- [ ] Невыполненная задача
- [ ] Невыполненная задача
- [X] Выполненная задача
```
- [ ] Невыполненная задача
- [ ] Невыполненная задача
- [X] Выполненная задача
```

# Ссылки

[InSales](http://insales.ru)
```
[InSales](http://insales.ru)
```

<https://insales.ru>
```
<https://insales.ru>
```
**Пример [один][1], пример [два][2].**

[1]: https://google.ru "Гугл" 
[2]: https://yandex.ru "Яндекс"
```
**Пример [один][1], пример [два][2].**

[1]: https://google.ru "Гугл" 
[2]: https://yandex.ru "Яндекс"
```

ссылка[^1]

[^1]: Заметка в конце блока или статьи. В данном случае - в конце блока.
```
ссылка[^1]
[^1]: Заметка в конце блока или статьи. В данном случае - в конце блока.
```
[Эмодзи](https://www.webfx.com/tools/emoji-cheat-sheet/)
# Таблица
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
```
| Влево  | По центру  | Вправо |
|:-------- |:---------:| --------:|
| первая ячейка | текст | |
| 2 | ~~зачеркнутая ячейка~~ | **жирная ячейка** |
| *курсив* | незачеркнутая ячейка | просто ячейка |
```
| Влево  | По центру  | Вправо |
|:-------- |:---------:| --------:|
| первая ячейка | текст | |
| 2 | ~~зачеркнутая ячейка~~ | **жирная ячейка** |
| *курсив* | незачеркнутая ячейка | просто ячейка |
```
# Списки
* Пункт 1
* Пункт 2
* Пункт 3
```
* Пункт 1
* Пункт 2
* Пункт 3
```

1. Пункт 1
2. Пункт 2
3. Пункт 3
```
1. Пункт 1
2. Пункт 2
3. Пункт 3
```
+ пример списка 
    * чтобы сделать подпункт, нажмите tab
        - подпункт подпункта
* второй пункт
```
+ пример списка 
    * чтобы сделать подпункт, нажмите tab
        - подпункт подпункта
* второй пунк
```


# Изображение

![alt](https://assets3.insales.ru/assets/1/6200/1103928/1551887044/main-header-img.png 'title')
```
![alt](https://assets3.insales.ru/assets/1/6200/1103928/1551887044/main-header-img.png 'title')
![альт](ссылка на картинку "описание при наведении")
```

# Код    
```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```
```js
<script type="text/template" id="popup_template">
    <h1>Hello, {username}!</h1>
    <p>Lorem ipsum dolor sit amet..</p>
</script>
<script type="text/javascript">
    var container = document.getElementById('popup_template');
    var containerContent = container.textContent || container.innerText;
    render_template(containerContent, {
        username: 'Bob',
    });
</script>
```
```scss /* или css */
@import "bower_components/tree-normalize/generic.normalize";
h1 {
 font-size:1.5em;
 font-weight: 300;
}
```
