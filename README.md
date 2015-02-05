# composer-demo-package-php-simple

## How load the library

```
{
    "repositories": [
        {
            "type": "package",
            "package": {
                "name": "demo/composer",
                "version": "dev-master",
                "source": {
                    "url": "https://github.com/juanber84/composer-demo-package-without-composer-json.git",
                    "type": "git",
                    "reference": "origin/master"
                },
            "autoload": {
                "files": ["functions.php"]
                }
            }
        }
    ],
    "require": {
        "demo/composer": "dev-master"
    }
}
```

## Usage

<?php
```php
require 'vendor/autoload.php';

greet();
```
