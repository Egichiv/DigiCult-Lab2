# Лаборторная работа по ИСР №2
## Что из себя представляет этот репозиторий?
Репозиторий будет отображать **работу с ветками** по модели **GitFlow**. <br>
(*Это второй репозиторий по данной лабораторной работе, т.к. на первом получилась, в определённом смысле, шляпа.*)

## Ветки:
### master:
Главная ветка, в которой будут "рабочие" версии проекта. Добавляются либо хотфиксы, либо полноценные следующие версии.
### hotfix:
Ветка, исходящая из master. Тут будут, соответственно, хотфиксы. Особо больше-то и не добавишь. После того, как хотфикс готов, изменения идут сразу в master.
### develop:
Ветка, исходящая из master. Тут уже будут храниться более серьёзные изменения, крупные изменения. После того, как всё готово, изменения идут в release.
### release:
Ветка, исходящая из develop. Тут будут храниться определённые доработки в этих крупных изменениях. Последние прикосновения, грубо говоря. После того, как всё готово, изменения идут в master. Выходит новая глобальная версия софта.
### feature:
Ветка, исходящая из develop. Тут будут храниться небольшие фичи, т.е. не самые крупные изменения. После того, как фича готова, изменения идут в develop.

## Что будет в ветках?
Только эта ридмишка и "main.cpp".
Изменения будут только в "main.cpp".

## Отдельные моменты
### Теги
Теги будут только в ветке master. В частности, на каждом изменении файла "main.cpp". Скорее всего только v1.0.0, v1.0.1, v1.1.0 .

### LFS
После всех основных действий закину используя LFS один большой файл. Скорее всего картинку большую.

### Submodules
Подмодулем будет репозиторий с предыдущей неудачной попыткой выполнить лабу.
Тоже сделаю после всех основных действий.

## Приятного просмотра!
(наверное).
