# Laravel 7 Türkçe Dil Dosyaları

## Kurulum

 1. Bu projedeki `tr` klasörünü Laravel 7 projenizdeki `resources/lang/` klasörü altına kopyalayın.
 2. Bu projedeki `tr.json` dosyasını Laravel 7 projenizdeki `resources/lang/` klasörü altına kopyalayın.
 3. Laravel 7 projenizdeki `config/app.php` dosyasında `locale`'i `tr` olarak değiştirin.
    ```php
    
    //'locale' => 'en',
    'locale' => 'tr',
    
    ```
Bu işlemlerden sonra Laravel 7 projenizdeki `lang` klasöründeki dosyalar şu şekilde listelenecektir. 

```sh
lang
├── en
│   ├── auth.php
│   ├── pagination.php
│   ├── passwords.php
│   └── validation.php
├── tr
│   ├── auth.php
│   ├── pagination.php
│   ├── passwords.php
│   └── validation.php
└── tr.json
```
    
## Değişiklikler

Son olarak yapılan değişiklikleri görmek için lütfen [CHANGELOG](CHANGELOG.md) dosyasına bakınız.

## Katkıda Bulunma

Detaylar için [CONTRIBUTING](CONTRIBUTING.md) dosyasını inceleyiniz.

### Güvenlik

Güvenlikle ilgili herhangi bir sorunla karşılaşırsanız lütfen ye@deligoz.me adresine e-posta gönderiniz.

## Katkıda Bulunanlar

- [Yunus Emre Deligöz](https://github.com/deligoez)
- [Tüm Katkıda Bulunanlar](../../contributors)

## Lisans

MIT Lisansı (MIT). Detaylı bilgi için [LICENSE](LICENSE.md) dosyasına bakınız.
