manesitu
========

## Back-end Setup

```bash
composer install
bin/console doctrine:schema:create
bin/console doctrine:fixtures:load
```

## Client setup
  * Install required dependencies `npm install`
  * Build client resources `npm run build`
