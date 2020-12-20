# Lumen Route List Display

[![Total Downloads](https://poser.pugx.org/marcha/lumen-routes-list/d/total.svg)](https://packagist.org/packages/marcha/lumen-routes-list)
[![Latest Stable Version](https://poser.pugx.org/marcha/lumen-routes-list/v/stable.svg)](https://packagist.org/packages/marcha/lumen-routes-list)


## Installation

1. Run
    ```
    composer require marcha/lumen-routes-list
    ```

2. Add service provider into **/bootstrap/app.php** file.
    ```php
    $app->register(Marcha\LumenRoutesList\RoutesCommandServiceProvider::class);
    ```
3. Run ```composer dump-autoload```

## Commands

```
php artisan route:list
```


## Author

<a href="http://www.sohelamin.com">Sohel Amin</a>

