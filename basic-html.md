<div align="center"><h1>Конспект: Основы HTML</h1></div>

## Оглавление.

- [**Глава 1: Знакомство**](#глава-1-знакомство)
  - [Азы HTML](#азы-html)
  - [Aзы CSS](#азы-css)
  - [Способ задачи стилей](#способ-задачи-стилей)
  - [Типы селекторов](#типы-селекторов)
    - [1. Селектор по тегу](#1-селектор-по-тегу)
    - [2. Селектор по классу](#2-селектор-по-классу)
  - [Имена классов.](#имена-классов)
  
- [**Глава 2: Структура HTML-документа**](#глава-2-структура-html-документа)
  - [Тип документа](#тип-документа)
  - [Кодировка](#кодировка)
  - [Стили](#стили)
  - [Ключевые слова и описание](#ключевые-слова-и-описание)
  - [Комментарии в HTML](#комментарии-в-html)
  - [Комментарии в CSS](#комментарии-в-css)
  - [Подключение скриптов](#подключение-скриптов)
    - [1. Встроенные скрипты](#1-встроенные-скрипты)
    - [2. Внешние скрипты](#2-внешние-скрипты)
    
- [**Глава 3: Разметка текста**](#глава-3-разметка-текста)
  - [Неупорядоченный список](#неупорядоченный-список)
  - [Упорядоченный список](#упорядоченный-список)
  - [Многоуровневый список](#многоуровневый-список)
  - [Списки определений](#списки-определений)
  - [Полужирный текст — важность](#полужирный-текст---важность)
  - [Курсивный текст — внимание](#курсивный-текст---внимание)
  - [Разделители](#разделители)
  - [Цитаты](#цитаты)
  - [Индексы](#индексы)
  - [Удаленный и исправленный текст](#удаленный-и-исправленный-текст)
  - [Преформатированный текст](#преформатированный-текст)
  - [Маркированный текст](#маркированный-текст)
  
- [**Глава 4: Ссылки и изображения**](#глава-4-ссылки-и-изображения)
  - [Абсолютные и относительные адреса](#абсолютные-и-относительные-адреса)
  - [Ссылка с якорем](#ссылка-с-якорем)
  - [Всплывающая подсказка](#всплывающая-подсказка)
  - [Альтернативный текст](#альтернативный-текст)
  - [Размеры изображения](#размеры-изображения)
  
- [**Глава 5: Таблицы**](#глава-5-таблицы)
  - [Отступ между ячейками таблицы](#отступ-между-ячейками-таблицы)
  - [Рамки таблицы: CSS](#рамки-таблицы-css)
  - [Заголовок таблицы](#заголовок-таблицы)
  - [Расположение заголовка таблицы: CSS](#расположение-заголовка-таблицы-css)
  - [Растягивание ячеек таблицы](#растягивание-ячеек-таблицы)
  - [Выравнивание содержимого ячейки: CSS](#выравнивание-содержимого-ячейки-css)
  - [Цвета таблицы: CSS](#цвета-таблицы-css)
  - [Размеры таблицы: CSS](#размеры-таблицы-css)
  
- [**Глава 6: Формы**](#глава-6-формы)
  - [Формы](#формы)
  - [Поле](#поле)
  - [Подпись поля](#подпись-поля)
  - [Кнопка для отправки формы](#кнопка-для-отправки-формы)
  - [Поле с галочкой](#поле-с-галочкой)
  - [Поле-переключатель](#поле-переключатель)
  - [Многострочное текстовое поле](#многострочное-текстовое-поле)
  - [Раскрывающийся список (селект)](#раскрывающийся-список-селект)
  - [Поле для загрузки файлов](#поле-для-загрузки-файлов)
  - [Скрытое поле](#скрытое-поле)
  
- [**Глава 7: Знакомство с HTML5**](#глава-7-знакомство-с-html5)
  - [Основные теги](#основные-теги)
  - [Теги блоков](#теги-блоков)
  - [Изображения в формате SVG](#изображения-в-формате-svg)
  - [Шрифты](#шрифты)
  - [Время](#время)
  - [Картинки с подписями](#картинки-с-подписями)
  - [Видео](#видео)
  - [Аудио](#аудио)
  
- [**Глава 8: Знакомство с HTML5**](#глава-8-формы-и-html5)
  - [Сброс введенной информации](#сброс-введенной-информации)
  - [Простая кнопка](#простая-кнопка)
  - [Кнопка-изображение](#кнопка-изображение)
  - [Альтернативная кнопка](#альтернативная-кнопка)
  - [Обязательное для заполнения поле](#обязательное-для-заполнения-поле)
  - [Поле выбора даты](#поле-выбора-даты)
  - [Поле выбора времени](#поле-выбора-времени)
  - [Список выбора возможных значений](#список-выбора-возможных-значений)
  - [Поле выбора числового значения](#поле-выбора-числового-значения)
  - [Поле поиска](#поле-поиска)
  - [Автофокус](#автофокус)
  - [Поля выбора: времени с учетом временной зоны, недели, месяца](#поля-выбора-времени-с-учетом-временной-зоны-недели-месяцао)
  - [Выбор из диапазона (ползунок)](#выбор-из-диапазона-ползунок)
  - [Область для вывода результата](#область-для-вывода-результата)
  - [Группировка полей формы](#группировка-полей-формы)
  - [Проверка введенной в поле информации](#проверка-введенной-в-поле-информации)
  - [Поле ввода телефона](#поле-ввода-телефона)
  - [Подсказка при заполнении поля](#подсказка-при-заполнении-поля)
  - [Поля для ввода: адреса сайта, электронной почты](#поля-для-ввода-адреса-сайта-электронной-почты)
  - [Поле выбора цвета](#поле-выбора-цвета)
  - [Группировка элементов списка](#группировка-элементов-списка)
  - [Запрет редактирования полей](#запрет-редактирования-полей)
  - [Автозаполнение полей](#автозаполнение-полей)
  - [Приоритет в переключении полей](#приоритет-в-переключении-полей)

## Глава 1: ```Знакомство``` 

### Азы HTML.  
Есть парные и одиночные теги.  
```Парные теги``` нужны, чтобы оформить некоторый участок теста.  
```Одиночные теги``` добавляют на страницу одиночный объект.  

Теги могут иметь ```атрибуты```.  
Некоторые теги есть смысл использовать только с атрибутами, например, ```img src```.  

### Азы CSS.  
```CSS``` (Cascading Style Sheets или Каскадные Таблицы Стилей)  

### Способ задачи стилей:  
```Инлайновые, встроенные стили``` — стили, приписываемые прямо в html-коде.  

#### 1. Через атрибут ```style```.  
```html
<p style="color: red;"> Текст </p>
```
#### 2. C помощью тега ```<style>```.  
```html
<style>  h1 { font-size: 28px; }</style>
```

#### 3. Внешние стили — стили, подключаемые с помощью тега ```<link>```.  
```html
<link href="external.css" rel="stylesheet">
```
Подключаемые стили содержат селекторы, чтобы браузер понимал, к какому тегу применять стили.  
```Селекторы``` указывают на то, к каким элементам применять стили, а ```свойства``` — на то, как именно отображать элементы.
```css
селектор { свойство1: значение1; }
```

### Типы селекторов. 
#### 1. Селектор по тегу.  
имя-тега { свойство: значение; }

```css
p { color: green; }
```

```html
<p>Текст</p>
```

#### 2. Селектор по классу.  
.имя-класса { свойство: значение; }

```css
.important { color: red; }
```
```html
<p class="important"> ... </p>
```

### Имена классов. 
Имя класса может содержать в себе ```латинские символы```, ```цифры```, ```символ дефиса -``` и ```подчёркивания _``` и начинаться оно должно с латинского символа.
  
  
  
## Глава 2: ```Структура HTML-документа```

### Тип документа.  
    ```<!DOCTYPE html>``` — современный вид декларации типа документа для HTML5.  

    ```<html lang="ru">``` — русский язык.  
    ```<html lang="en">``` — английский язык.  

### Кодировка.  
```html
<meta charset="utf-8">
```
Самая распространенная кодировка html-страницы. Кодировку лучше указывать выше, чем заголовок страницы, так как это поможет браузеру правильно определить кодировку заголовка.  

### Стили.  
Лучше подключать стили внутри ```<head>```, но это необязательно. Тег ```<link>``` будет работать и в другом месте страницы.

### Ключевые слова и описание.  
```html
<meta name="keywords" content="ключевые слова" />
<meta name="description" content="краткое описание страницы" />
```

### Комментарии в HTML.  
```html
<!-- Комментарии в HTML -->
```
```Комментарии не работают:``` внутри тегов ```<title>``` и ```<style>```, это единственные исключение.

### Комментарии в CSS.  
```css
/* h1 { color: red; } */
```

### Подключение скриптов.  
```HTML``` отвечает за структуру документа, ```стили``` — за его внешний вид, а ```скрипты``` — за поведение.  

Подключать скрипты можно в любом месте на HTML-странице, но лучше вставлять его в самом конце перед закрывающим тегом ```</body>```.  

#### 1. Встроенные скрипты.  
```javascript
<script>
  JavaScript-код
</script>
```

#### 2. Внешние скрипты.  
Подключение скриптов из внешних файлов с расширением ```.js```.
```javascript
<script src="external.js"></script>
```
  
  
  
## Глава 3: ```Разметка текста```  

### Неупорядоченный список.  
```html
<ul>
  <li>раз</li>
  <li>два</li>
</ul>
```

### Упорядоченный список.  
```html
<!-- начать нумерацию с цифры 3 -->
<ol start="3">
  <li>раз</li>
  <li>два</li>
</ol> 
```

### Многоуровневый список.  
Сначала нужно создать список первого уровня, а затем внутрь любого элемента этого списка, между тегами ```<li>``` и ```</li>```, добавить список второго уровня. При этом необходимо аккуратно закрывать все теги.  

Количество уровней в списках не ограничено. В многоуровневом списке можно использовать как упорядоченные, так и неупорядоченные списки.  
```html
<!-- Пример правильного кода: -->
<ul>
  <li>1
    <ul>
      <li>1.1</li>
      <li>1.2</li>
    </ul>
  </li>
  <li>2</li>
</ul>
```

```html
<!-- Пример кода с ошибкой: -->
<ul>
  <li>1</li>
  <ul>
    <li>1.1</li>
    <li>1.2</li>
  </ul>
  <li>2</li>
</ul>
```

В примере с ошибкой вложенный список вставлен не внутрь элемента списка, а между элементами, что недопустимо.  

### Списки определений.  
1. ```<dl>``` - сам список определений;  
2. ```<dt>``` - термин;  
3. ```<dd>``` - определение термина.  

Теги ```<dt>``` и ```<dd>``` пишутся парами внутри ```<dl>```.  

```html
<dl>
<dt>Термин</dt>
<dd>Определение</dd>

<dt>Второй термин</dt>
<dd>И его определение</dd>

<dt>Кошка</dt>
<dd>Шерстяное изделие развлекательного характера</dd>
</dl>
```

### Полужирный текст — важность.  
```<strong>``` — определяет важность отмеченного текста.  
```<b>``` — предназначен для выделения текста без придания ему особой важности.  

Лучше всего отличия этих тегов будут заметны людям, которые используют специальные настройки ОС, в частности, слепым и слабовидящим. Когда они включают функцию чтения текста, то «говорилка» будет интонацией выделять слова с тегом ```<strong>```. То же самое касается и тегов ```<em>``` и ```<i>```. Тег ```<em>``` «говорилка» будет выделять интонацией.  

### Курсивный текст — внимание.  
```<em>``` — определяет текст, на который сделан особый акцент — важность, меняющий смысл предложения.  
Например, если мы хотим подчеркнуть, что Кекс не любит питаться укропом (он больше за тунца), а любит только гонять его по полу.  

```<i>``` — обозначает текст, который отличается от окружающего текста, но не является более важным. Обычно так выделяют названия, термины, иностранные слова. Например, если мы хотим указать, что инспектор — это какой-то специальный термин.  

### Разделители.  
```<br>``` — перенос строки, одиночный тег.   
Для разделения текста на абзацы лучше использовать парный тег ```<p>```.  
```<hr>``` — горизонтальная линия-разделитель, одиночный тег.  

### Цитаты.  
```<blockquote>``` — предназначен для выделения длинных цитат, которые могут состоять из нескольких абзацев. Тег выделяет цитату как отдельный блок текста с отступами.  
```<q>``` — предназначен для выделения коротких цитат в предложениях. Текст внутри этого тега автоматически обрамляется кавычками.  
```<cite>```  — используется для того, чтобы выделить источник цитаты, название произведения или автора цитаты.  

### Индексы.
```<sup>``` — отображает текст в виде верхнего индекса.  
```<sub>``` — отображает текст в виде нижнего индекса.  
Эти теги можно использовать внутри друг друга для создания более сложных формул.  

Если нужно вставить очень сложную формулу в HTML-документ, лучше воспользоваться специальным языком разметки [MathML](https://ru.wikipedia.org/wiki/MathML).  

### Удаленный и исправленный текст.
```<del>``` — выделяет (зачеркнутым) текст, который был удалён в новой версии документа.  
```<ins>``` — выделяет (подчеркнутым) текст, который был добавлен в новой версии документа.  
Оба тега имеют атрибут ```datetime```, в котором можно указать дату и время, когда была внесена та или иная правка.  
Простейшим примером применения этих тегов может служить список ошибок. Когда ошибка исправлена, её помечают тегом ```<del>```, если найдена новая ошибка, то её добавляют в список и помечают тегом ```<ins>```.  
Атрибут ```datetime``` предназначен не для людей, а для компьютеров, поэтому дату и время там пишут в стандартизованном формате. При такой разметке программам легче разбирать документы и анализировать, когда произошли те или иные изменения.  

### Преформатированный текст.  
```<pre>``` — внутри текста отображаются все пробелы и переносы.  

### Маркированный текст.  
```<mark>``` — выделенный маркированный текст. В современных браузерах текст внутри ```<mark>``` подсвечивается жёлтым фоном.  



## Глава 4: ```Ссылки и изображения```

### Абсолютные и относительные адреса.  
1. Абсолютные адреса содержат в себе: протокол, имя сервера и путь.  
Например, в адресе ```https://htmlacademy.ru/courses:```  
```https://``` — это протокол  
```htmlacademy.ru``` — имя сервера, также называется домен или хост  
```/courses``` — путь  

Иногда абсолютные адреса записывают в укороченном виде: ```/courses```. В этом случае, браузер подставляет протокол и сервер текущей страницы.  

2. Относительные адреса ни содержат: ни протокола, ни имени сервера, а путь не начинается со слэша ```/```.  
Примеры:  
* ```courses/1```  
* ```./courses```  
* ```../../run/1```  

| Текущий адрес                        | Текущий адрес                       | Преобразуется в                     |
| -------------------------------------|-------------------------------------|-------------------------------------|
| ```http://site.ru/news/1```          | ```2```                             | ```http://site.ru/news/2```         |
| ```http://site.ru/news/1```          | ```..```                            | ```http://site.ru/```               |
| ```http://site.ru/users/profile/1``` | ```../../contacts```                | ```http://site.ru/contacts```       |

Использовать относительные адреса для навигации по сайту не рекомендуется. Однако относительные адреса бывают полезны, например, во внешних CSS-файлах.



### Ссылка с якорем.   
Можно задать адрес, состоящий из одного якоря, например:  
```html
<a href="#glava1">Глава 1</a>
```  
Идентификатор создаётся с помощью атрибута ```id```, который может быть задан у любого тега.  

### Всплывающая подсказка.  
```html
<a title="Подсказка" href="#">
``` 
Всплывает при наведении мышкой.  

### Альтернативный текст.  
```html
<img src="cat.png" alt="Кот в полном расцвете сил">
```
Показывается, если у пользователя отключены изображения или их нельзя загрузить.  

### Размеры изображения.  
1. Если задавать размер картинки в пикселях, то нужно использовать только цифры. Добавлять px не нужно, таков стандарт.  
2. Ширину иногда задают в процентах. Высоту обычно в процентах не задают.  
```<img width="50%" src="..."> ```  
3. Если задать только один из размеров, ширину или высоту, то вторую размерность браузер вычислит самостоятельно исходя из пропорций изображения.  



## Глава 5: ```Таблицы```

```<tr>``` — строка таблицы (от table row)  
```<td>``` — ячейка таблицы внутри строки (от table data).  
Теги ```<td>``` находятся внутри тегов ```<tr>```, а те внутри тегов ```<table>```.  
```<th>``` — ячейка-заголовок (от table header), аналогичен тегу ```<td>```.  
По умолчению текст в теге <th> является жирным и выравнивается по центру ячейки.  

### Отступ между ячейками таблицы.  
```html
<!-- Отступ между ячеейками таблицы равен 3 пикселям. -->
<table cellspacing="3">
```   
Однако для отступов лучше использовать CSS-стиль ```border-spacing``` или внутренние отступы (например, внутри ячеек) через ```padding```.  

### Рамки таблицы: CSS.  
```css
table {
  border: 3px solid black;
}
```  
Таким способом можно задать рамку таблице без HTML: ```<table border="5"```>.  
Рамки для отдельных сторон: ```border-top```, ```border-right```, ```border-bottom```, ```border-left```.  

```border-collapse: collapse;``` — убрать расстояние между ячейками; убирает двойные рамки: cхлопываются рамки соседних ячеек, а также рамки ячеек и внешнюю рамку таблицы.  
```border-collapse: separate;``` — значение по умолчанию, расклеить ячейки.  
```border-spacing: 5px;``` — отступ между ячейками 5 пикселей. Задается не для ячейки, а для таблицы, в отличии от ```padding```, который задается для ячеек.  

### Заголовок таблицы.  
```<caption>``` — тег для названия таблицы, находится сразу после тега ```<table>```, до остальных вложенных тегов.  

### Расположение заголовка таблицы: CSS.  
```caption-side: bottom;``` — поместить заголовок таблицы в теге ```<caption>``` под таблицу.  
```caption-side: top;``` — значение по умолчанию, заголовок таблицы в теге ```<caption>``` над таблицей.  
Выровнять тег ```<caption>``` по горизонтали можно с использованием свойств ```text-align.```  

### Растягивание ячеек таблицы.  
```<th colspan="2">``` или ```<td colspan="2">``` — объединить ячейку по горизонтали или растянуть ячейку на 2 ячейки.  
Ячейка с таким свойством растягивается на ячейку справа, а та ячейка не исчезает, а отодвигается, что добавляет в таблицу появляется новый столбец. Чтобы удалить его, нужно удалить ячейку, которая находится справа от растянутой.  
```<th rowspan="2">``` или ```<td rowspan="2">``` — объединить ячейку по вертикали или растянуть ячейку на 2 строки, то есть на следующую стоку.  
Ячейка, которая была под растянутой, отодвигается в своей же строке вправо, что добавляет в таблицу лишний столбец под последней ячейкой. Чтобы удалить его, нужно удалить ячейку, которая была под растянутой.  

* Объединять более 2 ячеек по вертикали или горизонтали тоже возможно.  
* Можно одновременно растягивать ячейку по вертикали и горизонтали, для этого нужно задать ячейке два атрибута: rowspan и colspan. 

### Выравнивание содержимого ячейки: CSS.  
```text-align: left;``` — выравнивание по горизонтали, ещё значения: ```center```, ```right```.  
```vertical-align: top;``` — вертикальное выравнивание по верху, ещё значения: ```middle```, ```bottom```.  

### Цвета таблицы: CSS.  
```background-color``` — цвет фона.  
```color``` — цвет текста.  
```border-color``` — цвет рамок.  

```td {color: brown;}``` — сменить цвет текста в таблице на коричневый.  

### Размеры таблицы: CSS.  
```width: auto;``` — ширина таблицы по умолчанию.  
```height: auto;``` — высота таблицы по умолчанию.  

* У таблицы есть минимальные размеры, которые зависят от содержания, меньше которых она не сожмётся, какое бы значение ширины или высоты ни задавалось.  
* Проценты при задании высоты обычно не работают.  
* Не обязательно прописывать размеры каждой ячейки, достаточно прописать размеры ячейки из первой строки и остальные ячейки будут такого же размера.  



## Глава 6: ```Формы```

### Формы.  
```html
<form action="https://echo.htmlacademy.ru" method="get">
  ```  
```<form>``` — тег для форм.  
```action``` — адрес отправки.  
```method``` — метод отправки, обычно используют ```get``` или ```post```, если не указывать этот атрибут, будет использоваться метод ```get```.  

Метод ```get``` посылает данные формы в строке запроса, то есть они видны в адресной строке браузера и следуют после знака вопроса.  

```html
https://www.google.com/search?q=htmlacademy
```  
Его лучше использовать в поисковых формах, потому что он позволяет получить ссылку на результаты поиска и передать её кому-то.  

Метод ```post``` посылает данные в теле HTTP-запроса и используется, когда нужно отправить много данных и ссылка на результат обработки этих данных не нужна. Например, при редактировании личного профиля.  

### Поле.  
```html
<form action="https://echo.htmlacademy.ru" method="get">
  <input type="text" name="search">
</form>
```  

```<input>``` — тег для большинства полей формы.  
У него есть 2 обязательных атрибута:  
* ```type``` — тип поля, влияет на отображение и поведение поля. Некоторых из типов полей: ```text``` - текстовое поле, тип по умолчанию и самый распространенный тип; ```password``` - заменяет текст при вводе на звездочки или точки.  
* ```name``` — имя поля, служит, чтобы правильно обработать данные на сервере.  

Другие атрибуты поля:  
* ```id``` — идентификатор поля, должен быть уникальным не только в пределах поля, но и на всей странице. Лучше всего использовать идентификатор, который отличается от имени поля.  
* ```value``` — заполняет поля нужной информацией по умолчанию, которая сразу же показывается.  
* ```placeholder``` — показывает пример текста, который нужно вводить.  

### Подпись поля.  
```<label>``` — внутри этого тега находится надпись к полю, если по ней кликнуть, то курсор переместиться на поле. Есть 2 способа привязать тег ```<label>``` к полю:  

1. Обернуть поле в тег ```label```.  
```html
<label>Подпись <input type="text" name="username"></label>
```  

2. С помощью for у подписи к полю ```<label>``` и ```id``` у поля ```<input>```, если обернуть поле в тег ```<label>``` нельзя.  
```html
<label for="user-field-id">Имя пользователя</label>
  много-много других тегов
<input id="user-field-id" type="text" name="username">
```  
Алгоритм следующий:  
* Добавляем к полю ввода идентификатор с помощью атрибута ```id```.  
* Оборачиваем текст подписи в тег ```<label>``` и добавляет атрибут ```for``` c таким же именем, что и ```id``` у поля.  

### Кнопка для отправки формы.  
```html
<!-- Кнопка для отправки формы -->
<input type="submit" name="open" value="Войти">
```
```submit``` — для создания кнопок.  
```value``` — задавать не обязательно, по умолчанию может быть значение ```Отправить```. Но если имя задано, то на сервер будут отправляться имя и значение кнопки.  

### Поле с галочкой.  
```html
<!-- Поле с галочкой, галочку по умолчанию задает атрибут checked. -->
<input type="checkbox" checked>
```
Чекбокс не подразумевает выбор одного элемента из нескольких. Поэтому если в одной форме есть несколько чекбоксов, то имена у них должны быть разными.

### Поле-переключатель.  
```html
<input type="radio" checked>
```
Обычно из размещают несколько, с вариантом по умолчанию.
У переключателей из одной группы должно быть: одинаковое name, но разные значения ```value``` и ```id```.  

### Многострочное текстовое поле.  
```html
<textarea id="comment-field" name="comment" rows="10">Текст комментария</textarea> 
```  
Атрибуты ```textarea```:  
* ```name``` — имя, как и у обычного ```input```.  
* ```id``` — идентификатор поля, как и у обычного ```input```.  
* ```rows``` — высота многострочного поля в количестве строк, целочисленное значение.  
* ```cols``` — ширина многострочного поля в символах.  
* ```value``` у многострочного поля отсутствует, так как надпись по умолчанию задается между тегами ```textarea```.  

### Раскрывающийся список (селект).  
```html
<select name="theme">
  <option value="light">Светлая тема</option>
  <option value="dark">Тёмная тема</option>
  ...
</select>
```

```<select>``` — раскрывающийся список, парный тег, есть атрибуты ```name``` и ```id```.  
```<option>``` — в этих тегах указываются варианты ответов, парный тег внутри select, атрибут value задает значение варианта ответа. Если при отправке формы у выбранного варианта задан ```value```, то на сервер отправится значение этого атрибута. В противном случае будет отправлен текст подписи.  

Мультиселект.  
```<select multiple>``` — возможность выбрать несколько вариантов из списка, кликая по ним с зажатой клавишей ```Ctrl``` на Windows или ```Command``` на OS X.  

Обычно при этом значении список открывается, становится видно несколько пунктов. Чтобы увеличить размер списка ещё используют следующий атрибут:  
* ```size``` — высота мультиселекта.  

```<option selected>``` — выбранное значение по умолчанию в списке.  

При отправке данных мультиселекта на сервер с PHP после имени в значении атрибута name ставятся символы квадратных скобок ```[]```. Например, ```<select name="days[]">```. Это необязательное требование для имени мультиселекта, а нужно только для корректной обработки данных в PHP.  

### Поле для загрузки файлов.  
```html
<form enctype="multipart/form-data" action="адрес файла">
  <input type="file" name="music1">
</form>
```

Поле для загрузки файлов, для работы необходимо добавить форме атрибут enctype со значением ```multipart/form-data```. Атрибут ```name``` для такого поля обязателен.  

### Скрытое поле.  
```html
<input type="hidden">
``` 
Его используют, когда в форме нужно отправить какие-то дополнительные служебные данные, которые не вводятся пользователем. Например, номер пользователя в форме оплаты.  



## Глава 7: ```Знакомство с HTML5```

Чтобы использовать html5, достаточно задать веб-странице такой тип документа - ```<!DOCTYPE html>```.  

### Основные теги.  
```<header>``` — хедер сайта или раздела.  
Хедер — это не только привычная шапка сайта с логотипом и меню, он может использоваться и как шапка какой-нибудь статьи или раздела сайта. Только в случае со статьёй хедер называют не шапкой, а вводной частью, в которой могут содержаться заголовки, оглавление и т.д.  

```<footer>``` — футер сайта или раздела.  
Подвал сайта, с копирайтами, контактной информацией и так далее. Но футер может использоваться и в других разделах сайта. Например, в статье в футере можно разместить дополнительную информацию: данные об авторе, дополнительные ссылки и так далее.  
* Может быть несколько на странице.  
* В футер включается не обязательно только подвал сайта. Там может быть какая-то заключительная информация.  

Если вы не хотите использовать классы для шапки и подвала сайта, то можете использовать селекторы ```body > header``` и ```body > footer```. Эти селекторы не повлияют на хедеры и футеры, вложенные более глубоко.  

```<main>``` — основное, не повторяющееся на других страницах, содержимое сайта. А значит, для его стилизации не нужны дополнительные классы.  
* Можно использовать на странице только 1 раз, в отличии от футера и хедера  
* Не нужно включать в тег <main> такое повторяющееся содержимое, как: навигация, копирайты и т.д.  

### Теги блоков.  
```<div>``` — контейнер общего назначения, не обязательно смысловой. Дивы используются для разметки мелких блоков, создания сетки и декоративных эффектов.  

```<article>``` — отделяемый, независимый и цельный раздел документа. Этот раздел можно в неизменном виде использовать в различных местах, в том числе и на других сайтах. Желателен заголовок внутри.  
* Примеры: статья, пост в блоге, сообщение на форуме, комментарий, твит, виджет ВК, и так далее.  
* Можно называть кратко — статья.  

Отдельная структура и иерархия заголовков у ```article```. Так как ```<article>``` должен быть независимым и легко встраиваемым куда угодно, то при разметке удобно считать его отдельной и самостоятельной страницей сайта. Это означает, что у него будет своя собственная структура (шапка, подвал, разделы) и иерархия заголовков, которая будет начинаться с заголовка первого уровня. Не нужно больше задумываться об окружении поста и подстраивать уровень заголовков в посте под это окружение, как часто приходится делать сейчас.  

```<section>``` — неотделимый от основного содержания контейнер, объединяющий содержание по смыслу.  
* Примеры: «О компании», список товаров, раздел личной информации в профиле и так далее.  
* Желателен заголовок внутри.  
* Можно называть кратко - раздел.  

Контейнеры ```section``` и ```article``` могут быть внутри друг друга. А может быть такая ситуация, когда контейнер ```section``` содержит в себе контейнер ```article```, который тоже содержит ```section```.  

```<nav>``` — тег для навигационных блоков. Теперь меню и блоки ссылок лучше оборачивать не в ```<div>```, а в ```<nav>```.  
* Лучше использовать для смысловой навигации, а не для всех групп ссылок.  
* Тегов <nav> может быть несколько.  

```<aside>``` — это дополнительное содержание, не связанное напрямую с основным. Ещё такие блоки часто называют сайдбарами или боковыми панелями.  

## Изображения в формате SVG.  
```html
<img src="image.svg" width="300" height="300">
```
Векторные изображения можно уменьшать и увеличивать без потери качества.  

### Шрифты.  
В HTML5 появилась возможность подключать и использовать на странице любые нестандартные шрифты. Веб-шрифты поддерживаются большинством современных браузеров.  

Подключение нестандартного шрифта в HTML:  
```html
<link href="//fonts.googleapis.com/css?family=PT+Sans:400&subset=cyrillic" rel="stylesheet" type="text/css"> 
```
После этого можно прописывать в стилях:
```css
font-family: "PT Sans", "Arial", sans-serif;
```

Подключение нестандартного шрифта в CSS:  
```css
@font-face {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  src:
    local("Roboto-Regular"),
    url("roboto.woff") format("woff");
}
```  
После этого можно прописывать в стилях:  
```css
font-family: "Roboto", sans-serif;
```

### Время.  
```html
<time datetime="2014-04-20">Вчера</time> 
```  
```<time>``` - специальный тег для обозначения даты и времени. C его помощью можно описывать даты одновременно и для человека, и для машины. Атрибуты:  
```datetime``` — указание даты в машиночитаемом формате ISO 8601, содержимое которого не отображается, а служит только для машины.  

### Картинки с подписями.  
```html
<figure>
  схема,
  график,
  диаграмма
  картинка
  и так далее
  <figcaption>Легенда - разъяснительный комментарий</figcaption>
</figure>
```  

### Видео.  
```<video>``` — тег для вставки видео. Атрибуты:  

* ```width``` и ```height``` — ширина и высота видео;  
* ```controls``` — отображается панель управления видео, атрибут без значений;  
* ```preload="none"``` — не загружать ничего в плеере;  
* ```preload="metadata"``` — загрузить служебную мета-информацию (длительность, первый кадр и т.д.);  
* ```preload="auto"``` — можно загрузить всё видео;  
* ```src``` — адрес видеофайла;  
* ```autoplay``` — автоматическое воспроизведение видео, атрибут без значений;  
* ```poster``` — адрес картинки-обложки, которая отображается, когда видео еще не загрузилось или не воспроизводится;  

Существует лишь несколько форматов видео, которые хорошо поддерживаются современными браузерами на данный момент, поэтому адреса подключаемых видео нужно указывать в этих форматах:  

* ```mp4``` (MPEG-4/H.264)  
* ```ogv``` (OGG/Theora)  
* ```webm``` (WebM)  

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.ogv" type="video/ogg">
  <source src="video.webm" type="video/webm">
</video>
```

Браузер из списка видеофайлов выбирает первый, который может проиграть и загружает его.  

Атрибут ```type``` не является обязательным, так как браузер умеет сам определять тип и кодеки, но указывая тип явно, мы помогаем ему не ошибиться.  

### Аудио.  
```<audio>``` — тег для вставки аудио. Атрибуты:  
* ```controls``` — отображается панель управления видео, атрибут без значений;  
* ```preload="none"``` — не загружать ничего в плеере;  
* ```preload="metadata"``` — загрузить служебную мета-информацию (длительность, первый кадр и т.д.);  
* ```preload="auto"``` — можно загрузить весь файл;  
* ```src``` — адрес аудиофайла;  
* ```autoplay``` — автоматическое воспроизведение видео, атрибут без значений;  

Для охвата большинства современных браузеров, достаточно использовать всего 2 формата аудио:  
* ```mp3```;  
* ```ogg```;  

Тег ```<source>``` работает также, как и у видео.  

```html
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
  <source src="sound.oga" type="audio/ogg">
</audio>
```  



## Глава 8: ```Формы и HTML5```

### Сброс введенной информации.  
```html
<input type="reset" value="Сбросить">
```
Cбрасывает введённые значения и возвращает изначально установленные.

### Простая кнопка.  
```html
<input type="button" value="Кнопка">
```  
При нажатии никаких действий не происходит, а все необходимые действия обычно задаются при помощи JavaScript.

### Кнопка-изображение.  
```html
<input type="image" src="enter.png" alt="Войти">
``` 
Кнопка с изображением. Работает аналогично кнопке ```submit```, но на сервер дополнительно передаются координаты точки, по которой был произведен щелчок.  

Как и у тега изображения у неё есть:  
* ```src``` — адрес изображения.  
* ```alt``` — альтернативный текст, отображаемый в том случае, если изображение не загружено.  

### Альтернативная кнопка.  
```html
<button>Календарь <img src="calend.png" alt="Описание"></button>
```
Тег, расширяющий возможности создания кнопок.
1. Внутри тега можно размещать любые HTML-элементы, в том числе изображения.  
2. ```type="submit"``` — по умолчанию у тега.  
3. ```type="reset"``` (сброс) и ```type="button"``` (избавляет кнопку от функциональности для дополнительный действий через JS) — работают как и в теге ```input```.  

### Обязательное для заполнения поле.  
```html
<input type="text" required>
``` 
При попытке отправить форму с незаполнеными обязательными полями браузер выведет всплывающее предупреждение.  

### Поле выбора даты.  
```html
<input type="date" name="date">
``` 
При клике на данное поле в форме всплывает календарик.  

### Поле выбора времени.  
```html
<input type="time" name="time">
``` 
Поле для выбора времени суток.  

### Список выбора возможных значений.  
```html
<!-- Значения, которые отображаются, когда начинают вводить текст в поле. -->
<input type="text" list="browsers" name="browser">
<datalist id="browsers">
  <option value="Firefox"></option>
  <option value="Chrome"></option>
  <option value="Safari"></option>
</datalist> 
```

Связывание текстового поля и списка: атрибут ```list``` у тега ```<input>``` и значение ```id``` у тега ```<datalist>``` должны быть одинаковыми.  

### Поле выбора числового значения.
```html
<input type="number" name="amount" id="amount" min="5" max="50" step="5">
```
Рядом с полем браузер автоматически подставляет две стрелочки для увеличения и уменьшения числового значения.
* ```min``` — минимальное значение.
* ```max``` — максимальное значение.
* ```step``` — величина шага изменения значения.

### Поле поиска.
```html
<input type="search" name="search" id="search">
``` 
Почти не отличается от обычного текстового поля. В некоторых браузерах внутри него появляется крестик для сброса введённого значения.

### Автофокус.
```<input type="text" autofocus>``` 
Сообщает браузеру, что именно на это поле нужно установить курсор по умолчанию. Автофокус улучшает процесс работы с формами, ведь пользователь избавляется от лишних щелчков мышки, там где они не нужны, а может сразу начинать вводить текст в поле.

### Поля выбора: времени с учетом временной зоны, недели, месяца. 
```<input type="datetime">``` — поле выбора даты с указанием времени (c учетом временной зоны).
```<input type="datetime-local">``` — поле выбора даты с указанием времени (без учета временной зоны).
```<input type="week">``` — поле выбора порядкового номера недели в году и года.
```<input type="month">``` — поле выбора месяца и года.

### Выбор из диапазона (ползунок).
```<input type="range" min="10" max="100" step="5">``` — поле выглядит как шкала с ползунком и позволяет выбрать число из некоторого интервала значений.
Как и у числового поля есть показатели минимального ```min```, максимального значения ```max``` и шага изменения значения ```step```.

### Область для вывода результата.
Область, куда выводятся какие-либо результаты вычислений, обычно полученные при помощи JavaScript.
```html
<form oninput="daysoutput.value=dayscount.value" action="/echo" method="post">
  <div class="half-width output-area">
    <output name="daysoutput"></output>
  </div>
  <div class="buttons">
    <input type="submit" value="Забронировать">
  </div>
</form>
```

### Группировка полей формы.
Когда формы становятся очень большими, возникает потребность зрительно отделить одни поля от других.
```html
<fieldset>
  <legend>Заголовок группы</legend>
  <input type="text">
  <input type="text">
  <input type="text">
</fieldset>
<fieldset>
  <legend>Заголовок группы</legend>
  <textarea></textarea>
</fieldset>
```

### Проверка введенной в поле информации.
```html
<input type="text" name="passport" pattern="[0-9]{3}-[0-9]{5}" required>
``` 
Автоматическая проверка формата введенных данных в поле. В данном случае регулярное выражение ```[0-9]{3}-[0-9]{5}``` задает паттерн ввода только числовой информации.

### Поле ввода телефона.
```html
<input type="tel" name="tel" pattern="[0-9]{1}-[0-9]{3}-[0-9]{3}" required>
``` 
Поля для ввода телефона. В мобильных браузерах при фокусе на такое поле появляется клавиатура, позволяющая вводить только цифры и символы телефонных номеров.

### Подсказка при заполнении поля.
```html
<input type="text" placeholder="Текст подсказки">
``` 
Текстовая подсказка для полей, в которые вводятся текстовые данные. Текст подсказки выводится внутри текстового поля, а при вводе значения — автоматически убирается.

### Поля для ввода: адреса сайта, электронной почты.
Оба поля автоматически проверяют формат введённых данных:
```html
<!-- для ввода электронной почты -->
<input type="email" name="email">

<!-- для ввода адреса сайта -->
<input type="url" name="url">
```

### Поле выбора цвета.
```html
<input type="color" name="color" value="#ff0000">
``` 
При клике на такое поле появляется окно с возможностью выбрать цвет из палитры. 
```value="#ff0000"``` — также можно задавать цвет по умолчанию.

### Группировка элементов списка.
В теге выбора вариантов ```<select>``` можно  объединять варианты ```<option>``` в группы. Вложенность групп не ограничена, внутрь каждой группы можно вложить другие группы.
```html
<select name="variants">
  <optgroup label="Группа вариантов 1">
    <option value="1">Вариант 1</option>
    <option value="2">Вариант 2</option>
    <option value="3">Вариант 3</option>
  </optgroup>
  <optgroup label="Группа вариантов 2">
    <option value="4">Вариант 4</option>
    <option value="5">Вариант 5</option>
    <option value="6">Вариант 6</option>
  </optgroup>
</select>
```

### Запрет редактирования полей.
```html
<input type="text" readonly>
``` 
Не дает пользователю изменять поле, но введенное значение можно: выделить, скопировать, отправить на сервер.

```html
<input type="text" disabled>
``` 
Не дает пользователю изменять поле, но введенное значение нельзя: выделять, копировать, отправлять на сервер.

### Автозаполнение полей.
Браузер может запоминать значения, вводимые в текстовые поля. При вводе первых букв текста выводится список сохранённых ранее значений, из которого можно выбрать подходящее.
```html
<!-- разрешить автозаполнение поля -->
<input type="text" autocomplete="on">

<!-- запретить автозаполнение поля -->
<input type="text" autocomplete="off">
``` 
```autocomplete="off"``` используется из соображений безопасности (например, чтобы не сохранялись пароли, номера банковских карт и т.д.).

### Приоритет в переключении полей.
```html
<input type="text" tabindex="3">
``` 
Задает порядок переключения элемента с помощь клавиши ```tab```.
* ```Положительное число``` — значения выстраиваются последовательно и переход между элементами происходит от меньшего значения к большему.
* ```0``` — элемент может быть выделен и достигнут с помощью последовательной навигации, однако порядок навигации определён платформой.
* ```Отрицательное число``` — элемент может быть выделен, однако не участвует в последовательной навигации.