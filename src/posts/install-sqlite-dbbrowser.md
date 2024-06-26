---
layout: post
title: Инструкция по установке SQLite и DB Browser
excerpt: В этой инструкции описан процесс установки программ для работы с SQLite.
date: 2023-11-06
updatedDate: 2023-11-06
tags:
    - post
    - it
---

В этой инструкции описан процесс установки программ для работы с SQLite.

## Установка для Windows

Установка на Windows проста, так как всё происходит через графический интерфейс.

### Установка SQLite3:

1. Скачайте установочный файл SQLite3 с официального сайта SQLite;
2. Запустите установочный файл;
3. Следуйте инструкциям мастера установки;
4. После установки SQLite3, найдите его ярлык на рабочем столе или в меню «Пуск»;
5. Щелкните правой кнопкой мыши по ярлыку и выберите «Свойства»;
6. В открывшемся окне нажмите кнопку «Изменить» рядом с «Рабочая папка»;
7. Выберите любую удобную для вас папку и нажмите «ОК»;
8. Теперь вы можете использовать SQLite3 из любой папки на вашем компьютере.

### Установка DB Browser for SQLite3

1. Перейдите на [официальный сайт DB Browser for SQLite](https://sqlitebrowser.org/dl/).
2. Прокрутите страницу вниз до раздела "Windows" и выберите ссылку для загрузки соответствующей версии DB Browser for SQLite.
3. Запустите загруженный установочный файл.
4. Следуйте инструкциям установщика, выбрав желаемое место установки и дополнительные настройки.
5. После завершения установки, запустите DB Browser for SQLite из меню Пуск или запускайте его через ярлык на рабочем столе.

## Установка для MacOS

Тут всё быстрее, но немного сложнее. Нам понадобится терминал и пакетный менеджер [Homebrew](https://brew.sh) или [MacPorts](https://www.macports.org/install.php).

1. Откройте терминал. Например, zshell или bash
2. Установите SQLite3, используя утилиту Homebrew или MacPorts.
    - Через Homebrew:
      `brew install sqlite3`
    - Через MacPorts:
      `sudo port install sqlite3`
3. После завершения установки вы сможете использовать SQLite3 из терминала.

### Установка DB Browser for SQLite3

1. Перейдите на [официальный сайт DB Browser for SQLite](https://sqlitebrowser.org/dl/).
2. Прокрутите страницу вниз до раздела "macOS" и выберите ссылку для загрузки соответствующей версии DB Browser for SQLite.
3. Загрузите .dmg файл, а затем откройте его.
4. Перетащите значок DB Browser for SQLite в папку "Приложения" для установки.
5. После завершения установки, можно найти DB Browser for SQLite в папке "Приложения" и запустить его оттуда.

## Установка для Linux Debian/Ubuntu

Тут всё быстрее, но немного сложнее. Нам понадобится терминал и пакетный менеджер apt, он уже встроен в дистрибутив.

1. Откройте терминал. Например, bash
2. Установите SQLite3, выполнив следующую команду в терминале:
   `sudo apt-get install sqlite3`
   Для других дистрибутивов Linux используйте соответствующий менеджер пакетов.
3. После завершения установки вы сможете использовать SQLite3 из терминала

### Установка DB Browser for SQLite3

1. Откройте терминал.
2. Выполните следующую команду для установки DB Browser for SQLite с помощью менеджера пакетов в вашем дистрибутиве:

```bash
# Для Debian и его производных. Например, Ununtu:
sudo apt-get update
sudo apt-get install sqlitebrowser
```

```bash
# Для Fedora:
sudo dnf install sqlitebrowser
```

```bash
# Для CentOS и его производных:
sudo yum install sqlitebrowser
```

-   Другие дистрибутивы Linux могут использовать свои собственные команды установки пакетов. Проверьте документацию дистрибутива или поищите инструкции для установки пакета DB Browser for SQLite.

3. После завершения установки, запустите DB Browser for SQLite из меню приложений или выполните команду sqlitebrowser в терминале.

Установив SQLite3, можно начать использовать его из командной строки или с помощью DB Browser для выполнения запросов к базе данных SQLite.
