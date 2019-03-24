# Clear cache
```sh
php bin/console cache:clear
```

# View all routes
```sh
php bin/console debug:router
```

# List all bundles
```sh
php bin/console config:dump-reference
```
# Assets
```sh
// make a hard copy of the assets in web/
$ php bin/console assets:install

// if possible, make absolute symlinks in web/ if not, make a hard copy
$ php app/console assets:install --symlink

// if possible, make relative symlinks in web/ if not, make a hard copy
$ php app/console assets:install --symlink --relative
```
# Available services

```php
php bin/console debug:autowiring
```
