# Markdown Notları

### İçerik
- [Başlıklar](#başlıklar)
- [Liste](#liste)
- [Tablo](#tablo)
- [Onay kutusu](#onay-kutusu)
- [Link oluşturma](#link)
- [Resim ekleme](#resin)
- [Kod blokları]
	- [Satır içi kod](#satır-içi-kod) 
	- [Kod bloğu](#kod-bloğu)
- [BETA](#beta)
	- [Not](#not)
	- [Uyarı](#uyarı)

---

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
```
[metin](link)
```
örnek: [github/spsofme](https://github.com/spsofme)



## Resim ekleme
```
![metin](resim bağlantısı)
```



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



## Beta
### Not
> **Note** <br>
> Note

### Uyarı
> **Warning** <br>
> Warning
