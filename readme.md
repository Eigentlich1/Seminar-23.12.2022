# Инструкция по работе с Git

## Что такое Git
***Git*** самая популярная реализация системы контроля версий. Самой распространенной системой ***Git*** является (*GitHub*)[https://github.com]
## Подготовка репозитория
Для создания репозитория используется команда *git init*. Для этого в терминале с открытой папкой репозиторием нужно ввевсти команду *git init*.
## Создание коммита
Для сщздания нового коммита используется команда *git commit*. Для этого в терминале с папкой репозиторием вводим команду *git commit* -m "сщщбщение к коммиту", сообщение к коммиту писать обязытельно!!!
## Перемещение между сохранениями
Для перемещения на другой коммит используется команда *git checkout*. Для этого необходимо в журнале найти ноиер нужного коммита, после чего в терминале с репозиторием написать команду *git checkout <номер коммита>*. После выполнения этой крманды мы попадаем в состояние **detatched head** в котором последущие коммиты не сохраняются. Для выхода из этого состояния нужно ввести в терминале команду *git checkout master*.
## Журнал изменений
Для просмотра истории изменений используется команда *git log*. Для этого в терминале с папкой репозиторием пишем команду *git log*.
## Создание веток в гит
Для создания веток в гит используется команда *git branch*. Для этого нужно ввести в терминале с папкой репозиторием ввести команду *git branch<название ветки>*.
## Объединение веиок в гит
Для слияния веток используется команда *git merge*. Для этого в терминале, в ветке к которой нужно присоединить, вводится команда *git merge <название присоединяемой ветки>*
## Разрешение конфликтов
При слиянии веток возможен конфликт если в разных ветках была изменена одна и таже строка текста. Для еготразрешения можно принять изменения в одной из веток или обоих. 

