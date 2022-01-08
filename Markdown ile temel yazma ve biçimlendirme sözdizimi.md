# Başlık Oluşturmak

Bir başlık oluşturabilmeniz için ```#``` iminden satır başında en az bir, en çok altı tane yazmalısınız.

## Örnek
```markdown
# Birinci düzeyde büsbüyük başlık
## İkinci düzeyde büyük başlık
### Üçüncü düzeyde küçük başlık
#### Dördüncü düzeyde küçücük başlık
##### Beşinci düzeyde ufak başlık başlık
###### Altıncı düzeyde ufacık başlık
```

# Birinci düzeyde büsbüyük başlık
## İkinci düzeyde büyük başlık
### Üçüncü düzeyde küçük başlık
#### Dördüncü düzeyde küçücük başlık
##### Beşinci düzeyde ufak başlık başlık
###### Altıncı düzeyde ufacık başlık
  
---
  
# Metin Biçimleri

```markdown
**Kalın metin yazmak için**
__Kalın metin yazmak için__

*Eğik metin yazmak için*
_Eğik metin yazmak için_

~~Ağdık metin yazmak için~~

**Kalın ve *yuvalı eğik* metin yazmak için**

***Kalın ve eğik metin yazmak için***
```

**Kalın metin yazmak için**  
__Kalın metin yazmak için__  

*Eğik metin yazmak için*  
_Eğik metin yazmak için_  

~~Ağdık metin yazmak için~~  

**Kalın ve *yuvalı eğik* metin yazmak için**  

***Kalın ve eğik metin yazmak için***  

---

# Alıntı Kod Ekleme

Bilgisayarda çalıştırdığımız kodları başkalarının okuyabilmesi için onlara özgü bir alan içinde paylaşmamız gerekir. Bunu üç tane tırnak (`) ya da iki tane tırnak (`) arasına alarak yapabilirsiniz. HTML'den bir örnek verelim. 

## Örnek
```markdown

  ```html
  <b>Kalın yazı</b> ```

``` 

## Çıktı Sonucu:
<b>Kalın yazı</b>

---

# Linkler (Örkler) Oluşturma

```markdown
Türkçe Yazılım Konatı ağbetine varmak için [buraya tıklayınız](https://turkce-yazilim-konati.github.io).
```

## Çıktı Sonucu:
Türkçe Yazılım Konatı ağbetine varmak için [buraya tıklayınız](https://turkce-yazilim-konati.github.io).

---

# Resim Eklemek

## Örnek
```markdown
![Bu bir resim](https://github.com/turkce-yazilim-konati/.github/raw/main/profile/images/t%C3%BCrk%C3%A7e_yaz%C4%B1l%C4%B1m_konat%C4%B1_github_duvar_resmi.jpg)
```
## Çıktı Sonucu:
![Bu bir resim](https://github.com/turkce-yazilim-konati/.github/raw/main/profile/images/t%C3%BCrk%C3%A7e_yaz%C4%B1l%C4%B1m_konat%C4%B1_github_duvar_resmi.jpg)

---

# Dizme Oluşturma

Çabucak bir dizme oluşturmak için ```-``` imi ya da ```*`` imini kullanmalısınız.

## Örnek
```markdown

- İlk dizme maddesi
- İkinci dizme maddesi

* Yıldızlı ilk dizme maddesi
* Yıldızlı ikinci dizme maddesi
```

## Çıktı Sonucu:

- İlk dizme maddesi
- İkinci dizme maddesi

* Yıldızlı ilk dizme maddesi
* Yıldızlı ikinci dizme maddesi

---

# Yuvalı Dizme Oluşturma

Yer yer dizmeleri yuvalı olarak oluşturmak isteyebilirsiniz. Yuvalamak istediğiniz maddeyi biraz içeri sokmanız yeterli. Üstteki maddenin ilk harfi ile çakışması önemlidir.

## Örnek
```markdown

- İlk dizme maddesi
  - İkinci dizme maddesi

* Yıldızlı ilk dizme maddesi
  * Yıldızlı ikinci dizme maddesi
```

## Çıktı Sonucu:

- İlk dizme maddesi
  - İkinci dizme maddesi

* Yıldızlı ilk dizme maddesi
  * Yıldızlı ikinci dizme maddesi

---

# Görev Dizmesi

Görev dizmelerinde kullanabileceğimiz ufak iki im vardır. ```[ ]``` bitmemiş görevler içindir. ```[X]``` bitmiş görevler içindir

## Örnek
```markdown

- [ ] Başlıklar oluşturulacak
  - [X] Ana başlıklar oluşturulacak
  - [ ] Alt başlıklar oluşturulacak

```

## Çıktı Sonucu:
- [ ] Başlıklar oluşturulacak
  - [X] Ana başlıklar oluşturulacak
  - [ ] Alt başlıklar oluşturulacak

---

# Tablo Oluşturmak

Ortalı yazı yazmak için ```:---:```
Sağlı yazı yazmak için ```----:```
Sollu yazı yazmak için ```:---```

## Örnek:
```markdown
| Başlık 1 | Başlık 2 |
| -------- | -------- |
| İçerik 1 | İçerik 2 |
```

## Çıktı Sonucu:
| Başlık 1 | Başlık 2 |
| -------- | -------- |
| İçerik 1 | İçerik 2 |

---

# Kaynaktan Tanımlı Link/Örk Oluşturmak

Yazı içerisinde birçok yerde aynı örkü kullanmak zorunda kaldığınızı düşleyin. Burada uzun uzadıya her yere ```[link/örk](upuzun_bir_örk_yolu)``` yazmak yorucu olabilir. Okuma güçlüğü çıkarabilir. Çözümü aşığıdaki örnekte. 

## Örnek:

```markdown

[Türkçe Yazılım Konatı] daha yeni kurulmuş idi. [Türkçe Yazılım Konatı]'nda ilk olarak [Karamel Programlama Dili]'ni yapmaya başlamıştık. [Karamel Programlama Dili]'nin ilk adı başka idi. Ancak şimdi [Karamel Programlama Dili] olarak söylüyoruz. [Türkçe Yazılım Konatı]'na katılanlar gün geçtikçe artar oldu. Biz de işlerimizi dallandırdık. [Türkçe Yazılım Konatı]'na katılmak isterseniz bekliyoruz.

[Türkçe Yazılım Konatı]: <https://turkce-yazilim-konati.github.io>
[Karamel Programlama Dili]: <https://turkce-yazilim-konati.github.io/karamel>

```

[Türkçe Yazılım Konatı] daha yeni kurulmuş idi. [Türkçe Yazılım Konatı]'nda ilk olarak [Karamel Programlama Dili]'ni yapmaya başlamıştık. [Karamel Programlama Dili]'nin ilk adı başka idi. Ancak şimdi [Karamel Programlama Dili] olarak söylüyoruz. [Türkçe Yazılım Konatı]'na katılanlar gün geçtikçe artar oldu. Biz de işlerimizi dallandırdık. [Türkçe Yazılım Konatı]'na katılmak isterseniz bekliyoruz.

[Türkçe Yazılım Konatı]: <https://turkce-yazilim-konati.github.io>
[Karamel Programlama Dili]: <https://turkce-yazilim-konati.github.io/karamel>

---

# Dipnotlar

Dipnotları markdown içinde dilediğiniz yerde yazabilirsiniz. Ancak çıktı sonucunda betin/sayfanın en dibinde görüntülenecektir.

## Örnek
```markdown

Burası örnek dipnotu[^1].

Birden çok satırda dipnotu kollunmak[^2].  

Adlandırılmış dipnotu kullanmak[^adlı].

[^1]: Benim kaynağım
[^2]: Birden çok satırda dipnot kullanabiliyoruz.
[^adlı]:
    Her ne kadar adlasak bile yazıların yanında sayılar ile işlemeye devam edecektir.
```

## Çıktı Sonuçları:

Burası örnek dipnotu[^1].

Birden çok satırda dipnotu kollunmak[^2].  

Adlandırılmış dipnotu kullanmak[^ad].

[^1]: Benim kaynağım
[^2]: Birden çok satırda dipnot kullanabiliyoruz.
[^ad]:
    Her ne kadar adlasak bile yazıların yanında sayılar ile işlemeye devam edecektir.
    
---
