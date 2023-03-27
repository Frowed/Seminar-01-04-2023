# Инструкция по работе с *Git*

## Что такое *Git*?
*Git* - это одна из реализация распределенных систем контроля версий. Самая популярный сервис *git* - это [GitHub](https://github.com)
## Подготовка репозитория
Для создания репозитория используется командаа *git init*. Для этого в терминале с открытой папкой, будущим репозиторием нужно написать *git init*.

## Создание фиксация


### Добавление файла к коммиту
Для того чтоб добавить файл к будущему коммиту используется команда *git add* . Для этого в терминале с открытой папкой репозиторием необходимо написать команду *git add (имя файла)*. 

### Выполнение коммита
Для того чтобы выполнить коммит используется команда *git commit* . Для этого в терминале с открытой папкой репозитория нужно написать *git commit -m (сообщение к коммиту)*. Сообщение писать **обязательно**

## Журнал изменений
Для просмотра историй изменений используется команда *git log*. Для этого в терминале нужно написать *git log*. также есть команда *git reflog*, о которой скажется ниже. 

## Подробный журнал
По умолчанию команда *git reflog* выводит журнал ссылок для указателя HEAD.

## Переключение между сохранениями
Для того чтобы перейти на другой коммит используется команда *git checkout* .Для этого в терминале с  открытой папкой репозитория нужно написать *git checkout (хеш коммита)*. Номер коммита можно взять из журнала изменений, о которой бюыло сказано выше. После выполнения это команды вы попадете в состоянее detached head и какие либо фиксации не будут ничего изменять. Для возврата в обычное состояние нужно написать команду *git checkout (название ветки, в которой вы работали)*. 

Ветки в Git
--------------------

Слияние веток и разрешение конфликтов
--------------------------------

Удаление веток
---------------------------