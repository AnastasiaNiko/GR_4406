# *Инструкция по работе с Git*_ 

## Регистрация в Git

Что бы идентифицировать пользователя нужно ввести имя пользователя и адрес электронной почты, для этого введите команды

*git config --global user.name "My Name"*

и

*git config --global user.email myEmail@example.com*

## Создание репозитория
Для инициализации репозитория введите команду 

* *git init*

## Создание коммитов

### _Основные команды:_

* *git add* - добывить файл к следущему коммиту
* *git commit -m"message"* -создание коммита
* *git log* -вывод на экран истории всех коммитов с их хэш-кодами
* *git status* - получить информацию о текущем состоянии

* *git checkout* -переход от одного коммита к другому

* *git checkout master* -вернуться к основному репозитарию
* *git checkout <номер коммита> -передвижение между репозитариумами

## Ветки в git

Для создания ветки используйте команду 

* *git branch <имя новой ветки>*

## Слияние веток

Для того чтобы добавить новую ветку в текущую используйте команду:

* *git merge*

## Удаление веток

Для удаления ветки введите команду

* *git branch -d <название ветки>


## *_Работа с GitHub_*

* *git merge [удалённый репозиторий]/[ветка]*

Позволяет внести изменения из ветки удалённого репозитория в текущую ветку локального репозитория

* *git push [удалённый репозиторий] [ветка]*

Загружает все изменения локальной ветки в удалённый репозиторий

* *git pull*

Загружает историю из удалённого репозитория и объединяет её с локальной. *pull = fetch + merge*

