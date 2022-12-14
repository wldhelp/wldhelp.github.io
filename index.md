<style>
div.highlight {
    border: 1px solid lightgray;
}
code.language-plaintext {
    border: 1px solid lightgray;
}
</style>

# Справка по блогу Владимира

**Примечание:** Для удобства можно открыть данную справку в браузере. Для этого нажмите сверху-справа значок квадрата со стрелкой вверх (Открыть в браузере).

**Примечание 2:** Чтобы скопировать текст, выделите его и нажмите `CTRL+C` (C - это Copy, т.е. Копировать). Или откройте данную справку в браузере.

Содержание:

- [I. Создать пост](#i-создать-пост)
- [II.	Общая информация](#ii-общая-информация)
- [III. Про редактор блога](#iii-про-редактор-блога)
- [IV. Про структуру блога](#iv-про-структуру-блога)
- [V. Про структуру поста](#v-про-структуру-поста)
- [VI. Про изображения для поста](#vi-про-изображения-для-поста)
- [VII. Дополнительно: ручное создание поста](#vii-дополнительно-ручное-создание-поста)
- [IIX. Решение проблем](#iix-решение-проблем)


## I. Создать пост

1. Нажать снизу-слева кнопку **Создать пост**.
2. Ввести **название** поста.
3. Нажать снизу-слева кнопку **Шаг 2**. Подождать **10 секунд**. Слева в **Проводнике** появится новый пост:
    
    ```
    Дата-Название-поста-на-англйиском.md
    ```
    
    Если его **открыть**, то появится следующий текст:
    
    ```
    ---
    title: "Название поста"
    ---
    
    Напиши здесь свой пост.
    
    ![Изображение](/nazvanie-tvoego-izobrazheniya.jpg)
    
    ```
4. Напиши свой пост.
5. Нажми **Добавить изображение**, чтобы добавить картинку к посту.
6. Выбери изображение и нажми **Open**. Изображение добавится слева в **Проводнике** к другим изображениям твоего блога.
7. Укажи в ссылке вместо **nazvanie-tvoego-izobrazheniya** название твоего изображения:
    
    ```
    ![Изображение](/nazvanie-tvoego-izobrazheniya.jpg)
    ```
    
8. Чтобы опубликовать пост, нажми кнопку **Опубликовать в Интернет**.
9. Через минуту пост будет доступен в твоём блоге: [wladimirvoronin.github.io](https://wladimirvoronin.github.io)


## II. Общая информация

Блог находится по адресу:

[wladimirvoronin.github.io](https://wladimirvoronin.github.io)

Посты в блоге имеют вид:

[wladimirvoronin.github.io/2022/08/01/kotyata](https://wladimirvoronin.github.io/2022/08/01/kotyata.html)

## III. Про редактор блога

Блог редактируется через программу **Visual Studio Code** (синий значок). Он состоит из двух частей: **панели проводника** слева и **редактора текста** справа.

## IV. Про структуру блога

Блог - это простая **папка**. А посты - это простые **текстовые файлы**. Они лежат в папке `_posts`. Изображения для постов лежат **рядом** с этой папкой. Это можно представить как:

```
Папка блога   
│
├───Папка _posts
│   │   Текстовый файл Пост-1.md
│   │   Текстовый файл Пост-2.md
│   │   Текстовый файл Пост-3.md
│   │   ...
│   
│   
│   Файл Картинка-1.jpg
│   Файл Картинка-2.jpg
│   Файл Картинка-3.jpg
│   ...
```

Новые неопубликованные посты подсвечиваются **зеленым** и имеют значок **U**.

## V. Про структуру поста

Пост - это **простой текстовый файл**. Пост имеет вид:

```
---
title: "Название поста"
---

Текст поста.

![Изображение](/Название-изображения.jpg)

```

## VI. Про изображения для поста

Создать пост без изображения очень просто. Но, чтобы добавить изображение, нужно сделать **два дополнительных шага**:

1. Добавить изображение в **папку блога**, нажав кнопку **Добавить изображение**.
2. Указать **ссылку** на него в посте вида:

```
![Изображение](/Название-изображения.jpg)
```

## VII. Дополнительно: ручное создание поста

Если автоматическое создание поста через кнопки **Создать пост** не работает, то можно создать пост вручную:

1. Слева в панели **Проводник** нажать **правой кнопкой** мыши по папке **_posts**. Выбрать **Создать файл**.
2. Ввести имя в виде **текущая-дата-название-поста.md** и нажать **Enter**. Например, **2022-06-25-koshki-leto.md**, что значит "25 июня 2022 года Кошки лето". Писать **английскими** буквами. **Без пробелов**. Не забыть добавить в конце **.md**.
3. Скопировать текст ниже:
    
    `Начало места копирования`
    ```
    ---
    title: "Название поста"
    ---
    
    Текст поста.
    
    ```
    `Конец места копирования`
    
    **Примечание:** чтобы скопировать, выделите текст и нажмите `CTRL+C`.
4. В созданном файле по пустому полю щелкнуть **правой кнопкой** мышки. Нажать **Вставить**.
5. Напиши название своего поста в поле **title** в кавычках.
6. Напиши свой пост там, где написано **Текст поста.**
7. Чтобы опубликовать пост, нажми кнопку **Опубликовать в Интернет**.
8. Через минуту пост будет доступен в твоём блоге: [wladimirvoronin.github.io](https://wladimirvoronin.github.io)


## IIX. Решение проблем

1. **Проблема:** У меня не получается создать пост. Как создать пост?
    
    **Решение:** Сначала нажми **Создать пост** и далее следуй инструкции.

2. **Проблема:** Я пишу текст с новой строки, чтобы были абзацы. Но после публикации они слипаются. Как их разбить?
    
    **Решение:** Между абзацами нужно добавить **пустую строку**. Пример:
    
    ```
    ---
    title: "Название поста"
    ---
    
    Это первый абзац.
    
    А это второй абзац, т. к. выше этой строки есть пустая строка.
    Это всё ещё второй абзац, т. к. выше пустой строки нет.
    
    А это уже третий абзац.
    
    ```
    
3. **Проблема:** Я создал простой пост без изображения, опубликовал его, и он не отображается в блоге. Что делать?
    
    **Решение:**
    - Нажми кнопку **Опубликовать в Интернет**
    - Подожди пару минут после публикации.
    - Проверь название поста в **Проводнике** слева. Оно должно быть вида **ГГГГ-ММ-ДД-Название-поста.md**. Не должно быть пробелов и русских букв. В конце должно быть `.md`.
    - Проверь структуру поста. Оно должно быть вида:
    
    ```
    ---                         ← Три минуса
    title: "Название поста"     ← Слово "title", затем ":", после пробел. Название поста должно быть в кавычках
    ---                         ← Снова три минуса
                                ← Пустая строка
    Текст поста.                ← Твой пост
                                ← Пустая строка
    ```
    
4. **Проблема:** Я добавил картинку, но в блоге в посте её нет. Как её отобразить?
    
    **Решение:**
    - Открой свой пост на сайте блога. Подожди **30 секунд**. Возможно картинка просто долго загружается.
    - Убедись, что файл картинки есть в **папке блога**. Найди слева в **Проводник** свою картинку. Нажми на неё. Убедись, что она отображается.
    - Убедись в **Проводник**, что файл картинки лежит **рядом** с другими картинками. Убедись, что он **НЕ** лежит в папке `_posts`.
    - Проверь, заменил ли в ссылке имя файла на **своё**. Оно находится внутри круглых скобок.
    - Проверь **ссылку** на картинку:
    
    ```
    ![Изображение](/nazvanie-tvoego-izobrazheniya.jpg)
    ↑↑     ↑     ↑↑↑             ↑               ↑   ↑
    ││     │     │││             │               │   └── Круглая скобка закрывается
    ││     │     │││             │               └── Точка и формат картинки .jpg
    ││     │     │││             └── Название твоей картинки
    ││     │     ││└── Косая черта
    ││     │     │└── Круглая скобка открывается
    ││     │     └── Квадратная скобка закрывается
    ││     └── Слово Изображение
    │└── Квадратная скобка открывается
    └── Восклицательный знак
    ```
    
    - Убедись, что картинка имеет формат **.jpg**.
    - Используй для названия картинки только **английские буквы**, **цифры** и **символ минуса** `-`. **НЕ** используй русские буквы и пробелы. **Хорошее название** картинки может быть таким: `2022-08-01-0001.jpg`, где сначала идет Дата, а затем номер картинки. Вместо пробелов используй символ минуса `-`.
    - **Ещё раз** обрати внимание на **обязательные символы** в ссылке: `!`, `[`, `]`, `(`, `/`, `)` и на `.jpg`. Обрати внимание на их порядок.
    
5. **Проблема:** Где посмотреть примеры оформления постов?
    
    **Решение:**
    Слева в панели **Проводник** есть старые посты. Можно посмотреть как они оформлены. И оформить свой пост так же.
    
6. **Проблема:** Я хочу добавить форматирование (жирность и т. п). Как это сделать? Есть пример поста со сложным форматированием?
    
    **Решение:** Ниже представлен пост, который имеет сложное форматирование:
    
    **Примечание:** чтобы скопировать, выделите текст и нажмите `CTRL+C`.
    
    Структура поста:
    
```
---
title: "Кошки лето"
---

## Кошка и еда

У меня часто возникает такое ощущение, что кошка Анюта вообще все человеческое
**очень хорошо понимает**. Предпочитает есть пищу, приготовленную для человека, т.е. со:

- специями,
- нормально посоленую,
- с перчиком.

Даже от сырой рыбы отказывается. Ест её только, когда сильно голодна. 

![](/2022-06-25-0001.jpg)

---

## Истории с кошкой

### История про еду

Как-то мы с соседями при ней отметили тот факт, что она не лазит по помойкам.
И однажды получилось так, что я несколько раз ходил туда-сюда, то на рынок, то в магазин.
И каждый раз она меня встречала возле подъезда и ждала, что я покормлю её.
Но мне было некогда и я говорил ей:

> Подожди немного, я тебе дам что-нибудь.

И вот я в очередной раз подхожу к дому и вижу кошку. Она, увидев меня,
не стала подходить ко мне, как всегда, а демонстративно направилась к помойке.
Я остановился и стал наблюдать. Она подошла к баку и оглянулась на меня.
Я чуть-чуть помедлил, и она тоже не стала прыгать на бак, а смотрела на меня
и как бы чего-то ждала. Я позвал её и она сразу же прибежала.
У меня возникло такое ощущение, что она **хитрит и пытается манипулировать мной**.

Статья на википедии про кошек: [Википедия](https://ru.wikipedia.org/wiki/Кошка)

```

Результат в блоге на сайте:

---

## Кошка и еда

У меня часто возникает такое ощущение, что кошка Анюта вообще все человеческое
**очень хорошо понимает**. Предпочитает есть пищу, приготовленную для человека, т.е. со:

- специями,
- нормально посоленую,
- с перчиком.

Даже от сырой рыбы отказывается. Ест её только, когда сильно голодна. 

![](/2022-06-25-0001.jpg)

---

## Истории с кошкой

### История про еду

Как-то мы с соседями при ней отметили тот факт, что она не лазит по помойкам.
И однажды получилось так, что я несколько раз ходил туда-сюда, то на рынок, то в магазин.
И каждый раз она меня встречала возле подъезда и ждала, что я покормлю её.
Но мне было некогда и я говорил ей:

> Подожди немного, я тебе дам что-нибудь.

И вот я в очередной раз подхожу к дому и вижу кошку. Она, увидев меня,
не стала подходить ко мне, как всегда, а демонстративно направилась к помойке.
Я остановился и стал наблюдать. Она подошла к баку и оглянулась на меня.
Я чуть-чуть помедлил, и она тоже не стала прыгать на бак, а смотрела на меня
и как бы чего-то ждала. Я позвал её и она сразу же прибежала.
У меня возникло такое ощущение, что она **хитрит и пытается манипулировать мной**.

Статья на википедии про кошек: [Википедия](https://ru.wikipedia.org/wiki/Кошка)

---
