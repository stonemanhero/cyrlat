# Cyrlat
Translate Serbian Cyrillic to Latin and vice-versa.

## Usage

use Stonemanhero\Cyrlat\Translate;

$textCyr = 'Ово је текст на ћирилици.';
$textLat = 'Ovo je tekst na latinici';

print Translate::process($textCyr);
print PHP_EOL;
print Translate::process($textLat, true);
