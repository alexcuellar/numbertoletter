# Number To Letter

Clase para convertir numeros a letras

Basado en la clase de @AxiaCore

## Instalacion

```php
    composer require andradedev/numbertoletter@devmaster
```

## Uso en laravel

Agregar a los servicios

```php
    'Andradedev\Numbertoletter\NumbertoletterServiceProvider',
```

Agregar un alias
```php
'Numbertoletter'    => 'Andradedev\Numbertoletter\Facades\NumbertoletterFacade',
```
## Uso

```php
	$num = "10008000.00";
    $letras = Numbertoletter::converter($num); 
    var_dump($letras); // string 'Doce mil pesos 12/100 M.N.' (length=26)
```