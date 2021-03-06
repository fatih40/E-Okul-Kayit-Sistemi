# E-Okul-Kayit-Sistemi


                         E-OKUL SİSTEMi RAPORU


##  Projenin Amacı

Eğitim kurumlarında Bir öğrencinin okula kaydından başlayıp, mezuniyetine kadar olan tum süreci içeren bir sistem geliştirdim.. Okula gitmeye gerek kalmaksızın online olarak internet üzerinden bilgi sahibi olması mümkün hale getirmek amacıyla bu projeyi yaptım.
Projenin web ve Mobilini geliştirmem durumunda daha kullanılabilir bir proje olur.
Proje Bütün Eğitim kurumlarını hedef almaktadır.

## Projenin Kazandirdiklari

Projeyi Java programlama diliyle IDE olarak NetBeans  ve Mysql veri işlemlerini kullandım.

**1)Mysql yapisi öğrendim .**<br/>
**2)Baska Sutunlardaki verileri ayni tabloya toplamayi öğrendim.**<br/>
**3)Forieng Key Kavramini Ogrendim.**<br/>
**4) Mysql  de insert Update Delete  Count  Ogrendim.**<br/>
**5)Login Formunda Database aldigim veriyi yazarak giriş yapma işlemini öğrendim.**<br/>

Veri çekme. Veri alma , veri kaydetme, veri güncelleme işlemlerini yaptım.<br/>
Ve en cok bu projenin kazandirdigi sey sabirdi, disardan cok basit bir problem gozuksede bir sorunu bir gun ugrastigim oldu  ve  Cok zaman harcamama sebeb oldu ama cok sey ogrendim.

Mysql kullanarak yaptığım ilk projem ve mysql veri işlemlerinde çok tecrübe kazandığım bir proje oldu .İlk projem olduğu için çok ayrıntılı bir proje olmadı ama ileri ki zamanlarda daha ayrıntılı bir şekilde geliştirmeyi  düşünüyorum .


## Projenin Tanitimi
Projeyi Çalıştırdığımızda Giriş paneli Çıkıyor ve burada 3 farklı giriş bulunmaktadır.
Bu Girisler: 

a)	**Yonetici girisi** <br/>
b)	**öğretmen girişi** <br/>
c)	**öğrenci girişi** <br/>


Ilk olarak gris yaptigimizda Bir giriş paneli karsimiza cikiyor.
### E okulGiris Formu
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/G%C4%B1r%C4%B1s.PNG)

Kullanıcı Yönetici girişi ,öğretmen girişi , öğrenci girişini seçtikten sonra herbirine kendini özel kullanıcı giriş ve login formu açılır.

## 1)Yonetici Girisi

İlk olarak Yönteci kendine özel sadece kendisini bildiği kullanıcı adı ve sifresi bulunmaktadır.
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Mudur%20giris.PNG)

Yonetici giriş yaptikdan sonra kendine ozel bir Ana sayfasi cikar.
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Mudur%20main.PNG)



Yonetici  Ogrenci , Ogretmen ve ders ekleyebiliyor,  silebiliyor, güncelleyebiliyor.


Sayfanin sol tarafındaki öğrenci ,ogretmen ve ders sayisi güncel olarak değişiyor.
Sayfanin en ust kisminda hangi kullanici adi neyse onun kullanici adi yaziyor.
 
 ![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/ogrenci%20ekle%20sayfasi.PNG)
 
Ogrenciyi kaydedildikten sonra tabloda otomatik olarak cikiyor.
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Ogrenci%20tablosu%20sayfasi.PNG)

Her bir öğrencinin kendine ozel bir  ID numarasi var.
Ogrenciye ID numarasi bildiriliyor.
Kayitli öğrenci tablosunda arama kisminda hangisi ismi yazarsan tabloda sadece o isim cikiyor.
Kayitli öğrenci tablosunda  silebiliyoruz ve güncelleyebiliyoruz.

![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Ogretmen%20yeni%20kayit%20sayfasi.PNG)

Ogretmen kaydedildikten sonra tabloda otomatik olarak cikiyor.
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Ogretmen%20kayit%20tablosu.PNG)

Her bir öğretmenin kendine ozel bir  ID numarasi var.
Ogretmene ID numarasi bildiriliyor.
Ogretmen kayit kisminda branşi kaydedildiği an ders adi otomatik olarak ekleniyor.
Ogretmen artik kendi ID numarasi ve sifresi ile kendi sayfasından giriş yapabilir.


## 2)Ogretmen Girisi
Yönteci  Ogretmene ozel ID  numarasini ve şifresini belirliyor sonra  öğretmene bildiriyor.
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Mudur%20giris.PNG)

Ogretmen bu sayfada kendine ozel ID numarasi yazarak basliyor .Sonra  sayfanin sagindaki tabloda öğrencileri gösteriyor.Bu tabloda otomatikmen seçtiği öğrencinin ID si yaziliyor ve daha sonra ogretmen öğrencinin notunu giriyor.
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/Ogretmen%20menu%20sayfasi.PNG)


**A)Ogrenci not ekleme**<br/>
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/ogrenci%20not%20ekleme%20sayfasi.PNG)

**B)öğrenci notlarinin tablosu**<br/>
![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/ogrenci%20not%20tablosu%20ogretmen%20icin.PNG)

Ogrenci notlarini tablosu ogretmen öğrencilerin notlarini görebiliyorlar.Sirasiyla hangi öğrenci hangi dersden kac puan olduğu güncel birsekilde gözüküyor.

## 3) Ogrenci Girisi

![Banner resmi](https://github.com/fatih40/E-Okul-Kayit-Sistemi/blob/master/E%20okul%20projesi%20%20images/ogrenci%20giris%20sayfasi.PNG)

Ogrenci burada kendine ozel verilmiş Kullanici ve Okul numarasini ile giriş yapıyor ve sadece kendi puanlarini goruyor.
Eger tabloda öğrenci kendi kulllanici adini veya şifresini yanlis girerse hicbirsey acilmiyor.














