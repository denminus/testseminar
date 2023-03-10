# Инструкция дла работы с Markdown

## Выделение текста
Чтобы выделить текст кусивом нужно обрамить звёздочками или знаком нижнего подчеркивания. Например *текст* или _текст_
Чтобы выделить текст полужирным нужно обрамить двумя звёздочками или знаком двойного нижнего подчеркивания. Например **текст** или __текст__
Альтернативные способы выделения жирным или курсивом нужны для того , чтобы мы могли совмещать оба этих способа. Например , _текст может быть выделен курсивом и при этом быть **полужирным**_. 
## Списки

Чтобы добавить пункты ненумерованного списки, необходимо пункты выделить звёздочкой или знаком +. Например 
* первый
* второй
* третий
+ четвертый

Чтобы добавить пункты нумерованного списки, необходимо пункты пронумеровать. Например
1. первый
2. второй

## Работа с изображениями
Чтобы вставить изображение в текст, достаточно написатьследующее: 
![name](cd7412da1e03af2ad39e.jpg)

## Ссылки
ergeargergheehqwegerge
gr
regeq
gqer
hgreqg

Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка"). Это — [без title]
(http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.

[1]: http://gb.ru/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short

Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.

## Таблицы
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML
## Цитаты

 Цитаты оформляются как в емейлах, с помощью символа `>
 > This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:
> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:
> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
> return shell_exec("echo $input |
$markdown_script");
### Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.


## Заголовки
# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6
В декоративных целях заголовки можно «закрывать» с
обратной стороны.
### Списки
Для разметки неупорядоченных списков можно использовать
или `*`, или `-`, или `+`:
- элемент 1
- элемент 2
- элемент ...
Вложенные пункты создаются четырьмя пробелами перед
маркером пункта:
* элемент 1
* элемент 2
* вложенный элемент 2.1
* вложенный элемент 2.2
* элемент ...
Упорядоченный список:
1. элемент 1
2. элемент 2
1. вложенный
2. вложенный
3. элемент 3
4. Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse id sem consectetuer libero luctus
adipiscing.
На самом деле не важно как в коде пронумерованы пункты,
главное, чтобы перед элементом списка стояла цифра
(любая) с точкой. Можно сделать и так:
0. элемент 1
0. элемент 2
0. элемент 3
0. элемент 4
Список с абзацами:
* Раз абзац. Lorem ipsum dolor sit amet, consectetur
adipisicing elit.
* Два абзац. Donec sit amet nisl. Aliquam semper ipsum
sit amet velit. Suspendisse id sem consectetuer libero
luctus adipiscing.
* Три абзац. Ea, quis, alias nobis porro quos laborum
minus sed fuga odio dolore natus quas cum enim
necessitatibus magni provident non saepe sequi?
Четыре абзац (Четыре пробела в начале или один tab).

это просто строка
