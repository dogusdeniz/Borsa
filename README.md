# Borsa
Ufak Çaplı Borsa İşlemleri Yapan C# Projesi


Merhaba,
Bugün sizlerle Dolar kuru hesaplayan ve anlık olarak dolar kurunu ekranda gösteren bir C# projesi yazacağız
öncelikle visual studio derleyicimizden (IDE) mizden yeni bir windows form projesi açıyoruz...
Gerçek dolar kurunu çekebileceğimiz bir api kullanacağım siteye açıklamadaki linkden erişebilirsiniz..
Bu Bir Eğitim Serisi Gibi Olacağından Bu Şekilde Adım Adım İlerlememiz Daha iyi Olacaktır...

Projemizin Adına Borsa diyorum



1.Yeni Proje Aç
2.Tasarımı Ayarla
3.Design Pattern Kullan
4.Kalıpları Tasarıma Uygula
5.Veri Tabanı Bağla
6.Projeyi Test Et
7.Entegrasyon

1. Aşama Tamamdır şimdi 2. Aşamaya Geçiyoruz
Renk seçimi konusunda size yardımcı olabilecek bir platformdur adobe color

geçici olarak bir logo bulacağım internetten siz kendiniz tasarlayabilirsiniz
nesnelerimizin simetrik olmasına dikkat etmeliyiz

yazım hataları olabilir kusura bakmayın

giriş sayfasının tasarımı tamamdır sırada diğer sayfaların tasarımı var

ve bu arada katmanlı mimari kullanacağımız için diğer katmanları oluşturmaya başlayacağım

yanlış projeyi açtım ve visual studio açık olduğu için silmeme izin vermedi

Data Katmanımız Api Kullanarak bize USD nin verilerini sağlayan Servis Katmanındaki Bilgiler ile yaptığımız 
işlemleri Katdetmemizi sağlayacak

şimdilik aklıma gelen katmanlar bunlar ileride ekleyeceğim katmanlar olabilir
Tasarıma Geri Dönüyorum

Sıra Anasayfamızın tasarımında Anasayfanın iskeleti bu şekilde olacak

Anasayfamızın Tasarımı bitmiştir 

şimdi sırada AL / SAT Sayfamızın Tasarımı Var

AL / SAT Sayfasına gerek olmadığını düşünüyorum bunu anasayfa üzerinden gerçekleştire bilir kullanıcılar
Anasayfa üzerinden hem al sat işlemleri yapıla biliyor hemde piyasa durumu gözlemlenebiliyor  bir sonraki bölümde
ilk arkaplan kodlarımızı yazmaya başlayacağız
