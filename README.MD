<h2>Cyrlat</h2>
<p>Translate Serbian Cyrillic to Latin and vice-versa.</p>

<h4>Usage:</h4>
```PHP
use Stonemanhero\Cyrlat\Translate;
$textCyr = 'Ово је текст на ћирилици.';
$textLat = 'Ovo je tekst na latinici';

print Translate::process($textCyr);
print PHP_EOL;
print Translate::process($textLat, true);
```
