# Инструкция по Git
## Основные команды работы с репозиторием
-  git init - инициализация
- git status - показывает текущее состояние гита, есть ли изменения, которые нужно закоммитить (сохранить)
- git add - добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита
-  git commit - зафиксировать или сохранить
- git log - журнал изменений. Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений
- git checkout - переключение между версиями. Для возврата в текущую версию вызвать git checkout master

## Команды по работе с удаленным репозиторием
- git clone -загружает все изменения и пытается слить все ветки на локальном компьютере и в удаленном репозитории.
- git push - отправляет свою версию репозитория во внешний репозиторий. При первом её использовании нужна авторизация.
- git pull -позволяет скачать все из удаленного репозитория и автоматически
сделать merge с нашей версией.

## Работа с GitHub: pull request.
- Делаем   (ответвление) репозитория fork
- Делаем git clone  СВОЕЙ версии репозитория 
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request
