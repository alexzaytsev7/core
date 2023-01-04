# Инструкция по работе с Git
**Git** (от англ. – Global Information Tracker) – это распределенная система управления версиями. Эта система позволяет хранить различные версии и возвращаться к различнм версиям проекта.

![Логотип Git](https://git-scm.com/images/logo@2x.png)
## Основные команды Git
* git init
* git status
* git add
* git commit
* git branch
* git graph
* git diff
## Краткое описание команд
1. *Git init* - Инициализация репозитория в существующей папке
2. *git status* - Проверка состояния файлов
3. *git add* - Добавление содержимого рабочего каталога в индекс (staging area) для последующего коммита
4. *git commit* - Cохраняет текущее состояние
5. *git branch* - Создвет новую ветку в репозитории
6. *git graph* - Показывает ASCII-граф истории ветвлений и слияний вместе
с выводом команды log
7. *git diff* - Вычисление разницы между любыми двумя Git деревьями

## 1 Погружение в ветки branch
 
### 1.1 Работа с черновиками

Если у нас несколько версий черновика, мы
можем вывести на экран ветку, где находимся,
командой git branch.

### 1.2 Совмещение двух вариантов текста
Чтобы слить любую ветку с текущей, вызываем
*git merge* <имя ветки для слияния с текущей>

### 1.3 Удаление веток

### 1.4 Работа с удаленными репозиториями в git
* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request 
### Спасибо 

