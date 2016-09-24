#Учебная сборка Loftschool Гордиенко Дмитрия

Stack:
 - Gulp 4.0

Getting started:

1. clone this repo
2. cd path/to/
3. npm install gulpjs/gulp-cli -g  // Install the latest Gulp CLI tools globally
4. npm install
6. run "gulp" command to start


К стандарному проекту Loftschool были добавлены 2 таска:

1. (sprite:png) генерирует спрайт из png картинок находящихся в папке source/sprite/png и закидывает его в папку sourse/sprite/images. Файл со стилями для спрайта закидывает в source/style/vendor (не забываем подключить их в пgulp/paths/css.foundation.js).
2. (copy:fonts) переносит шрифты из директории source/fonts в директорию assets/fonts.
