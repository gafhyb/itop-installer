# iTop extension Installer

Based on [composer/installers](https://github.com/composer/installers)
## Example `composer.json` File


```json
{
    "name": "you/ftp",
    "type": "itop-extension",
    "require": {
        "gafhyb/itop-installer": "~1.0"
    }
}
```

This would install your package to the `extensions/` folder of an iTop app
when a user runs `php composer.phar install`.

So submit your packages to [packagist.org](http://packagist.org)!