# image-php8-fix-opencart

[![Maintainability](https://api.codeclimate.com/v1/badges/2d44f8befc9ffa463e7b/maintainability)](https://codeclimate.com/github/brokeyourbike/image-php8-fix-opencart/maintainability)

Image library fix for PHP8 

In PHP8 `imagecreatefrom*` functions return `\GdImage` class [instead of resource](https://www.php.net/manual/en/class.gdimage.php).
