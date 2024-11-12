# Лабораторная работа №6: Система контроля версий

**Студент:** Подлинов Тимофей Евгеньевич

**Группа:** 4314

# Цель работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с 
локальным и удаленным репозиторием.

# Ход выполнения работы:

# Форк репозитория:
1. На странице репозитория [Kurtyanik/LR6](https://github.com/Kurtyanik/LR6) нажимаем кнопку "fork" в верхней части страницы

2. Создаем форк "Create fork"
![форк репозитория](assets/create_fork.png)

# Установка Git
Я скачал и установил Git с официального [сайта](git-scm.com).

# Настройка Git
После установки Git, настраиваем клиент, вводя имя пользователя и email:

```bash
git config --global user.name "Timofey Podlinov"
git config --global user.email "timapodina@gmail.com"
```

# Клонирование репозитория
Клонируем репозиторий на локальную машину:
```bash
git clone git@github.com:t1pcrips/LR6.git
```
# Добавление файла через GitHub
1. Добавляем [файл](assets/create_fork.png) "Add file" -> "Upload files" через интерфейс GitHub и затем подтягиваем изменения в локальный репозиторий

2. Подтягиваем изменения на локальную машину:
```bash
git pull
```

# Получение истории операций
Получаем историю операций для каждой из веток:

```bash
git log --all --oneline
```
![история опреация2](assets/check_log2.png)

```bash
git log -all --graph
```
![история опреация1](assets/check_log.png)

# Просмотр последних изменений
```bash
git diff
```
![поcледние изменения](assets/check_diff.png)

# Создание коммита через редактор - Goland
В Goland для создания коммита выбираем измененные файлы, пишем сообщение коммита и подтверждаем изменения.
![создание коммита goland](assets/goland.png)