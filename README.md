# spbu_diploma
## LaTeX шаблон для ВКР СПбГУ

#### **РЕПОЗИТОРИЙ ПОСТОЯННО ОБНОВЛЯЕТСЯ! РЕКОМЕНДУЮ НАЖАТЬ КНОПКУ WATCH**

(автор будет благодарен за звёздочку тоже :3)

## Cтруктура:

* spbudiploma.sty - стилевой файл

* titlepage.tex - титульник, который необходимо изменить под себя

* main_example.tex - пример основного файла. Рекомендуется создать свой main.tex, чтобы изменения в main_example.tex не мешали работе.

* [main_example.pdf](https://github.com/itonik/spbu_diploma/blob/master/main_example.pdf) - пример получившегося PDF файла

## Какие документы регламентируют верстку ВКР?
Их два. Первый регламентирует титульный лист (последняя страница):

http://edu.spbu.ru/images/data/normativ_acts/local/20180703_6616_1.pdf

Второй - всё остальное

http://edu.spbu.ru/images/data/normativ_acts/local/20181030_10432_1.pdf

## Как этим пользоваться?
Склонировать репозиторий к себе на компьютер, или, если вы пользуетесь онлайн-редактором,
скачать себе zip-архив и загрузить его. И обязательно регулярно заглядывать в репозиторий.

(Опция для просвещенных).
Можно форкнуть репозиторий, в нем писать свой диплом и периодически синкать его
с этим репозиторием.
Приобщиться к тайному знанию можно, например, тут

https://help.github.com/en/articles/syncing-a-fork

Рекомендую смысловые части разбивать на отдельные файлы и в main соединять их с помощью
`\input{<имя_файла>.tex}`. Посмотрите как подключается `titlepage.tex`, красота!

## Как структурировать диплом?
Диплом состоит из глав и параграфов. Для нас, глава - это `\section`, а параграф - это `\subsection`.
Также существуют **особые** главы - это "Введение", "Постановка задачи", "Обзор литературы",
"Выводы", "Заключение". Они обязательно присутствуют, не нумеруются и должны идти в том порядке, в
каком они идут в примере. Оформляются коммандой `\specialsection{<название_особой_главы>}`

## Хочу предложить изменение. Куда писать, что делать?
Я постоянно слежу за pull-request-ами. В случае, если ваш pull request не будет нарушать правил СПбГУ и сделает проект лучше, он немедленно будет принят.

Я доступен: vk.com/itonik, Telegram: @itonik