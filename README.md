# Примеры работ.

***

### Letusmake template

- Исходные файлы - https://github.com/z3plin/letusmake_template
- Скомпилированные файлы - https://github.com/z3plin/letusmake.io
- Результат - https://z3plin.github.io/letusmake.io/

### Reen template

- Исходные файлы - https://github.com/z3plin/reen
- Скомпилированные файлы - https://github.com/z3plin/reen.io
- Результат - https://z3plin.github.io/reen.io/

***

### Технологический стек

- Использовалась сборка [gulp-scss-starter](https://github.com/andreyalexeich/gulp-scss-starter)
  - Webpack для сборки Javascript-модулей
  - Препроцессор SCSS
  - CSS-сетка [smart-grid](https://github.com/dmitry-lavrik/smart-grid) на основе Bootstrap для быстрой адаптивной вёрстки
  - транспайлер [Babel](https://babeljs.io/) для поддержки современного JavaScript (ES6) в браузерах
  
- Файловая структура:
  - ```
    gulp-scss-starter
    ├── dist
    ├── gulp-tasks
    ├── src
    │   ├── blocks
    │   ├── fonts
    │   ├── img
    │   ├── js
    │   ├── styles
    │   ├── views
    │   └── .htaccess
    ├── gulpfile.babel.js
    ├── webpack.config.js
    ├── package.json
    ├── .babelrc.js
    ├── .bemrc.js
    ├── .eslintrc.json
    ├── .stylelintrc
    ├── .stylelintignore
    └── .gitignore
    ```
