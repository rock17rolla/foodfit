# Публикация FoodFit через GitHub

## Первая публикация

Загрузите содержимое этой папки в корень репозитория.

Commit message:

    release: FoodFit 2.3 Beta

После загрузки:

Settings → Pages → Build and deployment → Source → Deploy from a branch

Branch:

    main

Folder:

    / (root)

Нажмите Save.

## Git tag

Создайте тег:

    v2.3.0-beta

## GitHub Release

Release title:

    FoodFit 2.3 Beta

Description:

Скопируйте содержимое файла `RELEASE_NOTES_2.3.0-beta.md`.

## Следующие изменения

Для новой функции:

    feat: add <короткое описание>

Для исправления:

    fix: <короткое описание ошибки>

Для изменения интерфейса:

    ui: <короткое описание>

Для документации:

    docs: update <что изменено>

Когда готова новая версия:

    release: FoodFit X.Y.Z

После этого создайте новый tag и GitHub Release.
