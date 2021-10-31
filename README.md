# image-php8-fix-opencart

[![Maintainability](https://api.codeclimate.com/v1/badges/4816f3de3041b901fd08/maintainability)](https://codeclimate.com/github/brokeyourbike/image-php8-fix-opencart/maintainability)

Image library fix for PHP8 

In PHP8 `imagecreatefrom*` functions return `\GdImage` class [instead of resource](https://www.php.net/manual/en/class.gdimage.php).
