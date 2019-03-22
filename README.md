# Clear cache
```sh
php bin/console cache:clear
```
```sh
# View all routes
php bin/console debug:router
```
```sh
# List all bundles
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
