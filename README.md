# BookWave Releases

Публичное хранилище установочных APK BookWave.

## Правила публикации

- В каждом GitHub Release прикладывать готовый подписанный APK.
- Имя файла всегда одинаковое: `BookWave.apk`.
- Теги версий: `fix80`, `fix81`, `fix82` и далее.
- Название Release: `BookWave Fix80`, `BookWave Fix81` и т. д.
- В описание Release добавлять краткий список изменений.
- Исходный код приложения в этот репозиторий не загружать.

## Обновление из приложения

BookWave будет проверять последний опубликованный GitHub Release и сравнивать его с установленным `versionCode`.

Постоянная ссылка на APK последнего Release:

`https://github.com/zorinmihail1979-web/BookWave-Releases/releases/latest/download/BookWave.apk`

Все APK должны быть подписаны одним и тем же release-ключом, иначе Android не сможет установить новую версию поверх старой.
