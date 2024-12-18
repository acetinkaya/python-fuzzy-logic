## BULANIK MANTIK ve PYTHON UYGULAMALARI

Gelişen ve değişen teknoloji ile cihazların kontrolü üzerindeki ihtiyaç günden güne artmaktadır. Mevcut sistemlerin kontrolünde, yazılım dilleri üzerinde geliştirilen algoritmaların önemi büyüktür. Bulanık mantık (BM) sistemlerin kontrolü hayatımızın ayrılmaz bir parçası haline gelmiştir. Bulanık mantık hakkında yabancı dillerde çok sayıda çalışma mevcuttur. Bunlar arge araştırmaları, kitaplar, ders notları, makaleler ve bildiri çalışmalarıdır. Bu yayınlar arasında günümüz programlama dillerinden olan Python programlama dili ile hazırlanmış kapsamlı bir Türkçe Bulanık mantık kaynağı yer almamaktadır. Bu kitap Python programlama dili üzerinde geliştirilmiş bulanık mantık çalışmaları konusunda Türkçe literatüre katkı sağlayacaktır.  

Kitaptaki uygulamalar ve anlatımlar çok sayıda kişinin faydalanabilmesi açısından öğrenilmesi en kolay olan Python programlama dilinde hazırlanmıştır. Bu kitap 9 bölümden oluşmaktadır. Kitap içeriği örnek uygulamalara ağırlık verilerek Python programlama dili ile hazırlanmıştır. Uygulamaların açıklamaları Python kod blokları içerisinde ayrıntılı olarak verilmiştir. Kitabın birinci bölümde kitap ve bulanık mantık hakkında bilgilerin bulunduğu giriş bulunmaktadır. İkinci bölümde Python geliştirme ortamı anlatımı, kurulumu ve kütüphanelerinden bahsedilmiştir. Üçüncü bölümde bulanık mantığın avantajı, dezavantajı ve uygulama alanları verilmiştir. Dördüncü bölümde bulanık küme kavramı ve kural tabanı anlatılmıştır. Beşinci bölümde üyelik fonksiyonlarına yer verilmiştir. Altıncı bölümde sözel değişkenler ve IF-THEN kural yapısından bahsedilmiştir. Yedinci bölümde bulanık mantık uygulaması gerçekleştirirken izlenecek aşamalar anlatılmıştır. Sekizinci bölümde bulanık mantık sisteminin akış şeması yer almaktadır. Son olarak dokuzuncu bölümde bulanık mantık uygulamaları verilerek örnek Python kodları ile açıklamaları yer almaktadır.

Kitabın hedef kitlesini Fen, Sosyal ve Sözel alanlarında araştırma yapan tüm öğrenciler oluşturmaktadır. Bu yüzden Yazılım, Bilgisayar, Elektronik, Mekatronik, İktisat ve İşletme bölümlerinde ön lisans, lisans ve yüksek lisans öğrencileri için hazırlanmıştır. Özellikle ders içi proje ödevlerinde yardımcı kaynak olarak kullanılması amaçlanmıştır. Okuyucular bu kitaptan ve kodlardan yararlanarak kendi alanlarında Python programlama dilini kullanarak bulanık mantık sistemlerini geliştirebilirler. 

Bu kitabın hazırlanmasında kullanılan Python programlama dili ile bulanık mantık uygulamalarının bilimsel, akademik ve araştırma amaçlı tüm projelerinizde faydalı olmasını temenni ederim. Kitabın geliştirilme sürecinde gelecek baskılarında örnekler çoğaltılarak olası hata ve yanlışlıklarını giderilmesi planlanmaktadır. İlgi gösterecek olan herkese desteklerinden dolayı teşekkür ve saygılarımı iletiyorum.

Öğr. Gör. Ali ÇETİNKAYA  
İstanbul, 2023

---

## Author Info.:

- [**Ali Çetinkaya**](https://scholar.google.com.tr/citations?user=XSEW-NcAAAAJ)    
  İstanbul Gelişim Üniversitesi, İstanbul Gelişim Meslek Yüksekokulu, Elektronik Teknolojisi Programı, İstanbul / Türkiye  
  Istanbul Gelisim University, Istanbul Gelisim Vocational School, Electronics Technology Program, Istanbul / Turkey  
  
*For Correspondence: alcetinkaya@gelisim.edu.tr*

---

** Book Title / Kitap İsmi: BULANIK MANTIK ve PYTHON UYGULAMALARI

** ISBN No: 978-605-4827-98-5

** Basım Yılı / Published: 2023

** Yayınevi: İstanbul Gelişim Üniversitesi

** Kitap Yayın Bilgisi: [İGÜ Yayınları İnternet Sayfası](https://iguyayinlari.gelisim.edu.tr/tr/idari-duyuru-igu-yayinlarindan-106-kitap-bulanik-mantik-ve-python-uygulamalari)

** Kitap [Google Scholar](https://scholar.google.com.tr/citations?view_op=view_citation&hl=tr&user=XSEW-NcAAAAJ&sortby=pubdate&citation_for_view=XSEW-NcAAAAJ:9ZlFYXVOiuMC) ve [İGÜ Avesis Sayfası](https://avesis.gelisim.edu.tr/yayin/2d914227-34cf-492c-a9cd-86e10745f0b5/bulanik-mantik-ve-python-uygulamalari) 

---

## How to Cite / Nasıl Referans-Alıntı Yapılır?

- **IEEE**: A. Çetinkaya. Bulanık Mantık ve Python Uygulamaları. İstanbul: İstanbul Gelişim Üniversitesi 2023, pp.144

- **APA**: Çetinkaya, A., (2023). Bulanık Mantık ve Python Uygulamaları . İstanbul: İstanbul Gelişim Üniversitesi.

- **MLA**: Çetinkaya, ALİ. Bulanık Mantık ve Python Uygulamaları . İstanbul Gelişim Üniversitesi , 2023.

--- 

![alternatif metin](https://github.com/acetinkaya/python-fuzzy-logic/blob/main/Ali%20%C3%87etinkaya%20Python.jpg)

---

Proje Durumu:
İlgili paylaşımlar ve Python programlama dilinde yazılmış yazılım kodlarına sürüm güncellemeleri yaptıkça bu paylaşımları güncelleyeceğiz. GitHub bölümünden beğeni bildirimi olarak bir yıldız vererek çalışmalarımı destekleyebilirsiniz. Bilgi paylaşıldıkça büyür ve gelişir.

Katkıda Bulunma:
Çekme istekleri memnuniyetle karşılanır. Büyük değişiklikler için lütfen önce neyi değiştirmek istediğinizi görüşmek üzere ilgili Python kodunu belirttiğiniz bir soru - yanıt bölümü açın. 
 
Lisans: 
[MIT Lisansı](http://mit-license.org/) altında yayımlandı

Yazar ve Güncelleme Yapan: [Öğr. Gör. Ali Çetinkaya (MSc.)](https://github.com/acetinkaya) - 2023

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

Project Status:
We will update these shares as we make version updates to the related dependencies and software code written in Python programming language. You can support my work by giving a star as a like notification from the GitHub section. Knowledge grows and develops as it is shared.

Contributing:
Pull requests are welcome. For major changes, please open a question-and-answer section indicating the relevant Python code to discuss what you'd like to change first.

License:
Released under the [MIT License](http://mit-license.org/)

Authored and Maintained by [Lect. Ali Cetinkaya (MSc.)](https://github.com/acetinkaya) - 2023
