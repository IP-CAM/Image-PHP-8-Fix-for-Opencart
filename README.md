# image-php8-fix-opencart
Image library fix for PHP8 

In PHP8 `imagecreatefrom*` functions return `\GdImage` class [instead of resource](https://www.php.net/manual/en/class.gdimage.php).
