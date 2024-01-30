# Cyrlat
Translate Serbian Cyrillic to Latin and vice-versa.

## Usage
```php
use Stonemanhero\Cyrlat\Translate;
```

```php
$textCyr = 'Ово је текст на ћирилици.';
$textLat = 'Ovo je tekst na latinici';
```

```php
print Translate::process($textCyr);
print PHP_EOL;
print Translate::process($textLat, true);
```
