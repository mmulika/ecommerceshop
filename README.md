

Installation
------------

```bash
$ wget http://getcomposer.org/composer.phar
$ php composer.phar create-project sylius/sylius-standard project
$ cd project
$ yarn install
$ yarn build
$ php bin/console sylius:install
$ php bin/console server:start
$ open http://localhost:8000/
```

Troubleshooting
---------------

If something goes wrong, errors & exceptions are logged at the application level:

```bash
$ tail -f var/log/prod.log
$ tail -f var/log/dev.log
```

