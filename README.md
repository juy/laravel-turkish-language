# Laravel Türkçe dil dosyaları

> "[Laravel Türkiye](http://laravel.gen.tr/)" topluluğuna ait "[laravel-tr/Laravel5-lang](https://github.com/laravel-tr/Laravel5-lang)" deposundan klonlanıp devamlılığı sağlanmıştır.

## Sürümler ve ağaçlar

* Sürüm numaraları ve etiketler dil dosyalarını etkileyen [laravel/laravel](https://github.com/laravel/laravel/tags) sürümleridir, **laravel/framework sürümleri değildir**. Dil dosyaları için ayrıca tarafımızca verilen sürüm numaraları yoktur.
* "Master" ağacı güncel çalışma ağacıdır.
* Laravel 5.5 LTS için 5.5 ağacını kullanınız ve 5.5.* şeklindeki dosyalardan son sürümü indiriniz.
* Laravel sürümünüze göre mevcut en uyumlu etiketi indirip kullanabilirsiniz.



## Dil dosyası kurulumu

### Dosyaların kopyalanması

İndirdiğiniz dosyaların içindeki `tr/` dizinini Laravel'e ait olan `resources/lang/` dizini içerisine kopyalayınız.

### Laravel yazılımını Türkçe dilinde kullanma

`config/app.php` dosyasındaki, **locale** kısmındaki **en** ifadesini **tr** olarak değiştiriniz. Sonuç aşağıdaki gibi olacaktır:

```php
//'locale' => 'en', 
'locale' => 'tr', 
```

## Hata bildirimi ve öneriler

Tüm hata ve önerilerinizi Github üzerinden [bildirim açarak](https://github.com/juy/laravel-turkish-language/issues/new) yapabilirsiniz.

## Lisans
Açık kaynaklı olan bu proje [MIT lisansı][mit-url] ile lisanslanmıştır.

[mit-url]: http://opensource.org/licenses/MIT