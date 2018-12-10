# clean-code-ruby

Ruby için yalın kod konsepti uyarlanmıştır.

[clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript)'dan esinlenildi.

*Not: Burası hala geliştirme sürecindedir. Örnekler çoğunlukla JavaScript'den alınmıştır bu yüzden idiomatic olamayabilirler. Ruby'e özgü bir kod fark ettiğiniz zaman bunu belirtmekten çekinmeyin ve bir sorun bildirin. Hemen düzelteceğim. Ayrıca pull-request'leri de her zaman beklerim!*

## İçindekiler
  1. [Giriş](#introduction)
  2. [Değişkenler](#variables)
  3. [Fonksiyonlar](#functions)
  4. [Nesneler ve Veri Yapıları](#objects-and-data-structures)
  5. [Sınıflar](#classes)
  6. [SOLID](#solid)
  7. [Test](#testing)
  9. [Hata Yakalama](#error-handling)
  10. [Formatlama](#formatting)
  11. [Yorumlar](#comments)
  12. [Çeviriler](#translations)

## Giriş
![](http://www.osnews.com/images/comics/wtfm.jpg)

Robert C. Martin's kitabı olan Software engineering principles
[*Clean Code*](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882),
Ruby için uyarlanmış. Bu bir stil rehberi değiştir. Ruby'de
[okunabilir, tekrar kullanılabilir ve yeniden yorumlanabilir](https://github.com/ryanmcdermott/3rs-of-software-architecture) yazılımlar üretmek için bir rehberdir.

## **Değişkenler**
### Anlamlı ve telafuz edilebilir değişken isimleri kullanın

**Köyü:**
```ruby
yyyymmdstr = Time.now.strftime('%Y/%m/%d')
```

**İyi:**
```ruby
current_date = Time.now.strftime('%Y/%m/%d')
```
**[⬆ başa dön](#table-of-contents)**

### Aynı tipten değişkenler için benzer kelimeler kullanın

Konsept için bir kelime seçin ve ona bağlı kalın.
**Kötü:**
```ruby
user_info
user_data
user_record

starts_at
start_at
start_time
```

**İyi:**
```ruby
user

starts_at
```
**[⬆ başa dön](#table-of-contents)**

## Translations

Diğer diller de mevcuttur.

  - [Brazilya Portekizcesi](https://github.com/uohzxela/clean-code-ruby/blob/master/translations/pt-BR.md)

**[⬆ başa dön](#table-of-contents)**