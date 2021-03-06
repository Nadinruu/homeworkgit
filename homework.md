# Инструкция по работе с GIT

## Основные команды

* *git init* - **инициализация репозитория**
[Habr](https://habr.com/ru/company/ruvds/blog/599929/)

![git_init](Git_init.png)


* *git status* -**вывод статуса репозитория на данный момент времени**
[Habr](https://habr.com/ru/company/ruvds/blog/599929/)

* *git add* - **добавление файлу (файлам) версионности**
[Habr](https://habr.com/ru/company/ruvds/blog/599929/)

* [*git commit -m <massage>*](https://habr.com/ru/company/ruvds/blog/599929/)- **фиксация изменений**


* [*git log*](https://habr.com/ru/company/ruvds/blog/599929/)- **вывод журнала изменений**

* [*git diff*](https://habr.com/ru/company/ruvds/blog/599929/) - **вывод изменений по сравнению с предыдущим комитом**

* [*git checkout (хэш -номер)*](https://habr.com/ru/company/ruvds/blog/599929/) - **перемещение к определенному комиту**

* [*git checkout main(master)*](https://habr.com/ru/company/ruvds/blog/599929/) - **перемещение к актуальному состоянию**

## 2. Дополнительные команды

Чтобы после выполнения команды git log вернуть командную строку, необходимо нажать Q.

## 3. Команды по ветвлению

* *git branch* - **команда для вывода списка веток**

* *git branch <branch name>* - **создание новой ветки**

* *git checkout -b <name>* - **создание и переключение на новую ветку**

* *git merge* - **команда для слияния веток**

* *git branch -d* - **удалить слитую ветку**

* *git checkout* - **Переход на другую ветку**

* *git log -- graph* - **просмотр лог коммитов с визуализацией между ними**

* *git branch - m <name>* - **создание ветки и перемещение в нее**

## 4. Работа с удаленным репозиторием:

* *git remote add origin <адрес удаленного репозитория>* - **указываем адрес на удаленный репозиторий**

* *git push origin main* - **Отправлять изменения в удалённый репозиторий можно параметром push с указанием имени репозитория и ветки**

* *git pull* - **Для загрузки изменений из удалённого репозитория используется параметр pull. Он скачивает копию текущей ветки с указанного удалённого репозитория и объединяет её с локальной копией*
