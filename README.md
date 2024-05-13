# TcKimlikNoSorgulama
Php için T.C. Kimlik No Sorgulama API

Kullanımı: 

```php
<?php
require_once("TcKimlikNoSorgula.php");

if (TcKimlikNoSorgula::tcKimlikNo('10283995865')
    ->ad('kemal')
    ->soyad('dinç')
    ->dogumYili('2007')
    ->sorgula()) {
    echo 'Doğrulandı';
} else {
    echo 'Geçersiz';
}
```
