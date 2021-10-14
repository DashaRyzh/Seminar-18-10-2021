# Инструкция по работе с Git
## Что такое система контроля версий?

## Что такое Git

Гит - это одна из реализаций систем контроля версий. Позволяет управлять изменениями, создавать фиксации, ветки, а также сливать их.

## Подготовка репозитория

Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозиторий можно с помощью применения в папке команды (git init).

## Создание сохранений

Мы можем создавать сохранения версий файлов, они называются фиксациями или коммитами. Это делается командой (git commit) и ОБЯЗАТЕЛЬНО используется флаг (-m), после которого пишется сообщение в кавычках.

## Перемещение между сохранениями

Можно отменить изменения с помощью команд *git revert* и *git reset*.
*git revert* <номер коммита> отменяет изменения до указанной версии.
*git reset* --hard <номер коммита> отменит изменения до указанного коммита и затрёт всю историю изменений после этого коммита.

## Журнал изменений

## Ветки

Новая ветка создаётся с помощью команды *git branch* <название ветки>.

## Слияние веток и решение конфликтов

## Удаление веток

## Скачивание удалённого репозитория