## Реализовано
- После того как пользователь заполнил поля нажал на кнопку `Register` 
создается ползователь имеющий уникальный ключ 
всплывает окно с линком и нажав на нее переходит в страницу А

- в странице А есть все указанные функцыаналы которые нужны были реализовать
- при удаления данного ключа происходит редирект в главную удаляется ключ, но пользователь остается 
- при повторном нажатие на кнопку `Register` создается новый ключ

_реализовано максимально быстро так что могут быть моменты которые можно было украсить или оптимизировать_

# Run project locally

### Copy example environment
```
cp .env.example .env
```

### Install dependencies
```
composer install
```

### Generate application key
```
php artisan key:generate
```

### Run migrations
```
php artisan migrate 
```

### Run development server
```
php artisan serve
```
