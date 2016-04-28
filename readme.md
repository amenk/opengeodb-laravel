# Opengeodb Laravel

<a rel="license" href="http://creativecommons.org/licenses/by-nd/3.0/de/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/3.0/de/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-nd/3.0/de/">Creative Commons Namensnennung-Keine Bearbeitung 3.0 Deutschland Lizenz</a>.

## �ber


## Installieren
### Composer /Artisan
```
composer require equi/opengeodb-laravel:
```

oder in die composer.json die Zeile "equi/opengeodb-laravel": "~6.0", hinzuf�gen  
```
...
"require": {
        "php": ">=5.5.9",
        "laravel/framework": "5.2.*",
        ....
        "equi/opengeodb-laravel": "~6.0",
        ...
    },
    ...
```
```
composer update
php artisan vendor:publish
php artisan optimize
```

### Fehlende Dateien suchen
[OpenGeoDB](http://opengeodb.giswiki.org/wiki/OpenGeoDB) -> [Downloads](http://www.fa-technik.adfc.de/code/opengeodb/)
Welche Dateien braucht ihr?  
Pflicht:
```
opengeodb-begin.sql
opengeodb-end.sql
opengeodb_hier.sql
changes.sql
```

Optional je Nachdem welches Land ihr ben�tigt paarwei�e laden:  
```
AT.sql
AThier.sql
BE.sql
BEhier.sql
CH.sql
CHhier.sql
DE.sql
DEhier.sql
LI.sql
LIhier.sql
```

Die Dateien scheinen veraltet diese werden aber in changes.sql aktualisiert  

### Konfiguration

```

```

### Datenbanken erstellen und f�llen
```
php artisan migrate --seed
```

## Einbinden/Benutzen

## Zus�tzliche Daten
