# Task Board / Todo Management app

This is a task board / todo management application built with Laravel, Vue and TailwindCSS.

### Requirements

- Composer
- Node
- NPM / Yarn

### Installation

This project use Laravel 5.6 as Framework.

1 - Create a .env file

```bash
$ cp .env.example .env
```

_SQLITE is the default provider_

2 - Install everything and run production

```bash
$ composer install
$ npm install
$ npm run prod
```

Now you can go to tasklist.test/ and BOOM working =)

### Testing

This projects has unit / feature tests, simple run phpunit

```bash
$ vendor/bin/phpunit tests/
```
