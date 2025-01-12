# Тестовый удаленный репозиторий

# Инструкция по работе с Git

## Создание Git-репозитория
* берём локальный каталог, который не
находится под версионным контролем, 
и превращаем его в репозиторий.
* клонируем существующий репозиторий 
из любого места.

## Контроль версий
*Контроль версий необходим, чтобы:*
* хранение версий сводится к созданию копий информации на компьютере или сервере. 
Функцию возврата реализуют за счёт восстановления предыдущих версий. 

Таким образом, _система контроля_ — это реализованная возможность замены информации 
с использованием сохраненных версий.
хранить разные версии проекта;
возвращаться к разным версиям проекта.
*Контроль версий* (контроль исходного кода) — практика, которая позволяет отслеживать
изменения исходного кода и управлять ими.

## Команды Git
* git init
* git add
* git commit -m
* git log
* git checkout
* git branch
* git merge
## Списки
* Курсив это (*) или (_). Например, *Курсив* или _Курсив_.
* Полужирный это (**) или (__). Например, **Полужирный** или __Полужирный__. 
* Нумерованный список:
1. Перый
2. Второй
3. Третий и т.д.

## Удаленный репозиторий
1. Копировать внешний репозиторий на свой ПК можно командой _git clone_.
Команда _git clone_ составная: она не только
загружает все изменения, но и пытается слить 
все ветки на локальном компьютере и в
удаленном репозитории.
* _git pull_ - эта команда позволяет скачать все 
из текущего репозитория и автоматически
сделать merge с нашей версией.
2. Отправить свою версию репозитория во
внешний репозиторий поможет команда git
push. При первом её использовании нужна
git pull авторизация.
* _git push_-эта команда позволяет отправить нашу
версию репозитория на внешний
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ 
на внешнем репозитории.

3.  _pull request_
команда для предложения изменений, запрос на вливание изменений в репозиторий. В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают
команду pull request. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала
пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем
клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет
изменения командой push в свой аккаунт на GitHub и даёт команду pull request. 
