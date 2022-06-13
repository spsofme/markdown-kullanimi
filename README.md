# Markdown Kullanımı

### İçerik
- [Metin biçimlendirme](#metin-biçimlendirme)
	- [Kalın](#kalın)
	- [İtalik](#italik)
	- [Üstü çizili](#üstü-çizili)
- [Başlıklar](#başlıklar)
- [Liste](#liste)
- [Tablo](#tablo)
- [Onay kutusu](#onay-kutusu)
- [Link oluşturma](#link-oluşturma)
- [Resim ekleme](#resim-ekleme)
- [Alıntı yapma](#alıntı-yapma)
- [Kod blokları](#kod-blokları)
	- [Satır içi kod](#satır-içi-kod) 
	- [Kod bloğu](#kod-bloğu)
- [Daraltılmış bölüm](#daraltılmış-bölüm)
- [Çizgi ekleme](#çizgi-ekleme)
- [BETA](#beta)
	- [Not](#not)
	- [Uyarı](#uyarı)

---

## Metin biçimlendirme
### Kalın
`**metin**` : **metin**

### İtalik
`*metin*` : *metin*

### Üstü çizili
`~~metin~~` : ~~metin~~



## Başlıklar
```md
h1 : # başlık 1
h2 : ## başlık 2
h3 : ### başlık 3
h4 : #### başlık 4
h5 : ##### başlık 5
h6 : ###### başlık 6
```


## Liste
```  
- eleman 1
- eleman 2
	- alt eleman 1
	- alt eleman 2

1. eleman 1
	1. alt eleman 1
	2. alt eleman 2
2. eleman 2
```
örnek:
- eleman 1
- eleman 2
	- alt eleman 1
	- alt eleman 2

1. eleman 1
	1. alt eleman 1
	2. alt eleman 2
2. eleman 2



## Tablo
| servis | port |
| ------ | ---- |
| ftp | 21 |
| ssh | 22 |
| telnet | 23 |
| http | 80 |



## Onay kutusu
- [ ] Ders çalış
- [x] Oyun oyna
- [ ] Evi temizle
- [x] Dinlen



## Link oluşturma
`[metin](link)` şeklinde link oluşturulabilir. Ayrıca link'e title özelliği eklemek istersek `[metin](link "title")` şeklinde kullanabiliriz. <br>
normal link     : [github/spsofme](https://github.com/spsofme) <br>
title özellikli : [github/spsofme](https://github.com/spsofme "github adresim")



## Resim ekleme
```
![metin](resim bağlantısı)
```



## Alıntı yapma
```
> metin
```
örnek:
> metin



## Kod blokları
### Satır içi kod
```
`Ctrl + c`
```
örnek: `Ctrl + c`



### Kod bloğu
```
```[dil]

.. kod

```‏‏‏‏‏‏‏‏   
```
örnek:
```cpp
#include <iostream>
using namespace std;

int main() {
	int sayi;
	cout << "bir sayi girin: ";
	cin >> sayi;
	cout << "girdiginiz sayi: " << sayi;
	return 0;
}
```



## Daraltılmış bölüm
```
<details><summary>Tıkla</summary>
<p>Metin</p>
</details>
```
örnek:
<details><summary>Tıkla</summary>
<p>Metin</p>
</details>



## Çizgi ekleme
```
---
```
örnek:

---


## Beta
### Not
> **Note** <br>
> Note

### Uyarı
> **Warning** <br>
> Warning
