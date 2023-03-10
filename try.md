# Инструкция по работе с git

Git это программа для сохранения версионности проекта

## Создание репозитория

Для того, чтобы создать (иниацилизировать) новый
репозиторий в текущей папке импользуется команда:

    **git init**

## Проверка состояния репозитория

Чтобы проверить состояние репозитория нужно выполнить
команду:

    **git status**

## Добавление изменений к отслеживанию

Для того, чтобы добавить изменение к отслеживанию(в индекс), нужно выполнить команду:

    **git add <filename>**

## Добавление контрольных точек в репозиторий

    **git commit[]**

### Флаг [-а]

добавляет контрольную точку в репозиторий

### Флаг [-m]

добавляет сообщение о сделанных изменениях

## Просмотр журнала изменений

Чтобы просмотреть журнал изменений нужно выполнить команду:

    **git log**

### Флаг --oneline

выводит журнал всех изменений одной строкой

### Флаг --all

Выводит журнал всех изменений

### Флаг --oneline --all

Выводит журнал всех изменений одной строкой

## Просмотр изменений в текущем сеансе работы

чтобы посмотреть изменения в текущем сеансе работы нужно выполнить команду:

    **git diff**

Команда:

    **git diff <hash1> <hash2>

показывает изменения в двух сохранениях

## Ветвления

![git emblem](python.png)

## Ветвления

Ветвления в гит нужны для для решения каких-то определенных задач.Команда:

git branch branch_name

## Просмотр всех веток

чтобы прсмотреть список всех веток используется команда:

git branch

## Сливание веток

Чтобы слить ветки, нужно перейти в ветку с которой нужно слить другую и выполнить комаду:

git merge branch_name


Это были основные команды по веткам

## Удаленные репозитории

### Новые репозитроии

Чтобы создать новый репозитории в терминале выполнить команду :

 git init


### Удаление ветки

Чтобы удалить ветку которая больше не нужна нужно выполнить команду:

git branch -d <имя ветки>

## Удаленные репозитории

Чтобы создать удаленный репозитории нужно зайти в свою учетную запись github, создать новый репозиторий, в терминале выполнить команды котырые предлагает github, такого типа:

it remote add origin https://github.com/Maksim-coder-sys/SeminarC-_2.git
git branch -M master
git push -u origin master

### Добавление commitов с локального репозитория в удаленнный

Для того,чтобы добавить commitы с локального в удаленный репозиторий, нужно выполнить команду:

git push
