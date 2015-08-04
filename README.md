# TcKimlikNoSorgulama
Php için T.C. Kimlik No Sorgulama API

Kullanımı:

```php
if (TcKimlikNoSorgula::tcKimlikNo('11111111111')
    ->ad('İsim')
    ->soyad('Soyisim')
    ->dogumYili('1991')
    ->dogrula()) {
    echo 'Doğrulandı!';
} else {
    echo 'Geçersiz';
}
```
