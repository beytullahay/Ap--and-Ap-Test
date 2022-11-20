# Api-and-ApiTest


## API (Apllication Programming Interface)(Uygulama Programlama Arayüzü)
```
- Temel olarak iki uygulamanın birbiriyle iletişim kurmasını sağlar.
```


## API Örnekleri

```
-Google Haritalar
-Analytics
-Takvim
-Youtube
-Translate
-Twitter ve Facebook login
```




## API Tipleri
```
1- SOAP API

internet üzerinden bilgileri yada mesajları aktarma protokolü
-HTTP
-TCP/IP
-XML Formatlıdır.
-Kurumsal projelerde tercih edilebilir.
-.Net, java kullanılabilir.
- WSDL ve XML dosyaları ile çalışıyor.

2- REST API
Client ile server arasında hızlı ve kolay şekilde iletişim kurulmasını sağlar
veri transfer yöntemidir
HTTP üzerinde çalışılır
XML veya JSON hatta text olarak bile kullanılabilir.
Bir çok uygulama bunu kullanır
Platformdan bağımsız çalışır.
WSDL kullanmaz.
```




## Web Servisi Nedir? SOA(service oriented architecture)
```
Web ve mobil olarak proje geliştirdiğimiz varsayalım. 
Her biri için UI, Business.dll, DataAccess.dll,  olarak tek tek yazılması gerekiyor.
Bir modül veya değişiklik olduğunda örn webde değişiklik olduğunda mobilede onu replace etmek lazım.
Bunu önlemek için Servis host ile servis yazılır.
Burada Servis, Business.dll ve DataAccess.dll bulunur.
Servisi istediğimiz dille yazabiliriz. (C#, Java, Php, Phyton vb.).
Bunun sayesinde webde ve mobilde sadece UI kısmı olur. Backend ortak olmuş olur.


Web servies(XML) (Dosya boyutu büyük)
RESTful Services Web APIs
.Net Remoting (Eski daha az tercih ediliyor)
WCF (Windows Communication Foundation) 

SOAP
- HTTP ve TCP kullanır.
- Sadece XML ile işlem yapılır.
- WSDL ve XML ile aktarılabilir.
Mesaj bölümleri --> Envelope --> Header , Body ve Fault'dan oluşur


WSDL
- Metot , Paramtere ve Web servis adresi
- xml'de element, binding falan adı altında gelir. 

UDDI
```





## REST servis HTTP metodları
```
-Post   yeni veri ekle, kişi ekle falan
-Get    getir, listele
-Put    Ekle veya var olanın üzerine yaz güncelle
-Delete sil, id ismi vererek silme falan
-Patch  belirli bölümde işlem yap
-Options
```



## Sonuç durum kodları
```
100'ler bilgilendirici
200'ler başarılı
300'ler yönlendirme
400'ler istemci hataları
500'ler sunucu hataları

200 OK, 404 not found, 400 bad request gibi
```
 
 
 
## SOAP ve REST farkları
```
-SOAP güvenlik sağlamak daha kolay protokolü vardır.
-SOAP sadece XML iken REST Json, Xml ve Test kullanabilir.
-REST daha hızlıdır Json okumak daha kolaydır.
-Önbelleke işlemi REST'de daha kolaydır.
-REST tasarlanması kolaydır.
-Bir istemci SOAP ile ilgili tüm bilgileri bilmek zorundadır. REST sadece url bilse yeter. 
```


 
## API Testi araçları
```
Postman (Soap ve Rest Apı yapılır)
SoapUI (Çok sık kullanılır. Soap ve Rest Apı testi yapılır)
Katalon Studio (API ve Mobil testi yapılır)
Rest Assured ()
Karate DSL (Open Source)
```





 
## API Test Tipleri
```
İntegration Test    -- bağımsız iki yazılımda bilgilerin doğru aktarılıp aktarılmadıgı testi denilir.
Load Test           -- Sistem üzerindeki dar boğazları ortaya çıkartmak için
Regression Test     -- Değişiklik yapılan ve yapılmayan yerlerde hataları bulmak 
Securty Test        -- Güvenlik testi
User Interface Test -- Arayüz testi
Functional Test     -- Bileşen ve fonksiyonların testleridir.
Stress Test         -- Sisteme zorlayarak nerede kırıldığını görmek için.
```


## Web Servisi ile Api farkı
```
Her Api web servisi değildir.
Tüm Apilere internet üzerinden erişilemeyebilir

Her web servisi bir Apidir
Web servislerine her zaman ağ üzerinden erişilebilir.
```


 
## WSDL Formatları
```
Types (Tipler):       XML standartlarına uygun olarak tanımlanmış veri tipleridir.
Messages (Mesajlar):  İşlemin veri elemanlarını tanımlanmaktadır.
PortType (Port Tipi): Web servislerindeki işlevleri açıklanmakta ve mesajların oluşturulması sağlanmaktadır.
```



 
## TEST OTOMASYONU
```
Test otomasyon mühendisinin temel anlamda görevi, 
geliştirilen ürünler üzerinde baştan sona kontroller yapması ve kullanıcının ürünü rahat bir şekilde kullanmasını sağlamaktır.
```








