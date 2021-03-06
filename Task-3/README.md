# Simple CRUD in Symfony 5.0.8 based on Encore with Vue and Axios

> A simple Book List

Demo: https://books.spoko.space/

## Requirements:
Symfony 5.08+

PHP 7.3.11+

Composer 1.10.5+

Node v12.16.3+ (it's recommended to use nvm for switching node version)

## Build Setup

``` bash
# install dependencies
npm install
```

## Migrations:
``` bash
php bin/console make:migration
php bin/console doctrine:migrations:migrate
```

## Run watch files
``` bash
yarn encore dev --watch
```

## Screenshots:

### Home (books list based on Vue.js + Axios):
<img src="https://raw.githubusercontent.com/CNK001/tests/master/Task-3/DOCS/request-examples/books-list-frontend-based-on-scss.png">
JSON source:
<img src="https://github.com/CNK001/tests/blob/master/Task-3/DOCS/request-examples/book-get-all.png?raw=true">


### Add book (saving via axios):
<img src="https://raw.githubusercontent.com/CNK001/tests/master/Task-3/DOCS/request-examples/add-book-front.png">
JSON source:
<img src="https://github.com/CNK001/tests/blob/master/Task-3/DOCS/request-examples/add-book.png?raw=true">
### 

### Delete book:
<img src="https://github.com/CNK001/tests/blob/master/Task-3/DOCS/request-examples/book-delete-front.png?raw=true">
JSON source:
<img src="https://github.com/CNK001/tests/blob/master/Task-3/DOCS/request-examples/book-delete.png?raw=true">



## TODO:

### Update book (TODO):
JSON source:
<img src="https://github.com/CNK001/tests/blob/master/Task-3/DOCS/request-examples/book-update.png?raw=true">
