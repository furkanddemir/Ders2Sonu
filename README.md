# C# EĞİTİM KAMPI PROJELERİ  

Bu repo, Murat Yücedağ hocamın YouTube üzerinde eğitimini verdiği **“C# Eğitim Kampı”** süresince tamamladığım projeleri içermektedir. Aşağıda her projeye dair detayları bulabilirsiniz:  

---

📌 **Proje 1: Merhaba Dünya!** 

Bu projede öncelikle konsola yazı yazdırmayı öğrendim. İlk kod olarak “Merhaba Dünya” yazdırarak C# Eğitim Kampı’na adımımı atmış bulundum. Yazdırma Komutları, String Değişkenler ve Int Değişkenler kullanıldı. 

---

📌 **Proje 2: Değişkenler (Variables)**  

Bu projede Double, Char, Int gibi farklı veri türlerinde değişkenler tanımlayarak kullanıldı. Veri tipleri ve değişkenler farklı örnekler yapıldı.

---

📌 **Proje 3: Karar Yapıları (Making Decision)**  

Bu projede, Char değişkenler ile karar yapıları, mod işlemleri, switch-case kullanarak hesap makinesi örneği projesi yapıldı.  

---

📌 **Proje 4: Döngüler (Loops)**  

Bu projede ilk olarak For, Foreach ve While Döngüsü konusu işlendi ve bu döngüleri kullanarak bir örnek yapıldı.  

---

📌 **Proje 5: Döngüler ile Yıldız Şekilleri**  

Bu projede iç içe for döngüleri kullanılarak yıldızlarla farklı şekiller konsol ekranında gösterildi.

---

📌 **Proje 6: Diziler (Arrays)**  

Bu projede, diziler ile birden fazla bilgiler depolamayı ve bu bilgileri döngüler kullanarak farklı örneklerde uygulamalar yapıldı.

---

📌 **Proje 7: Foreach Döngüsü ve Sınav Sistemi Örneği**  

Bu projede, foreach döngüsünü daha yakından inceleyip bir sınav sistemi simülasyonu oluşturuldu. Öğrencilerin sınav notlarını alarak ortalamaları hesaplandı ve geçme/kalma durumlarını belirlendi.  

---

📌 **Proje 8: Metotlar (Methods)**  

Bu projede, Void Metotlar, Geriye Değer Döndüren Metotlar, Geriye Değer Döndürmeyen String Parametreli Metotlar, Geriye Değer Döndüren String Parametreli Metotlar, Geriye Değer Döndürmeyen Int Parametreli Metotlar,  Geriye Değer Döndüren Int Parametreli Metotlar ve son olarak Örnek Uygulama yapıldı.

---

📌 **Proje 9: Veri Tabanı Ürün-Kategori Bilgi Sistemi**  

Bu projede öncelikle veri tabanı bağlantısı yapıldı ve MSSQL ile tablolar ve bu tabloların içeriği verilerle dolduruldu. Kullanıcıdan tablo seçimi yapılarak seçilen tablonun konsol ekranı üzerinde gösterilmesi yapıldı.

---

📌 **Proje 10: Veri Tabanı Ürün-Kategori Ekleme Silme ve Güncelleme İşlemi**  

Bu projede öncelikle veri tabanı bağlantısı yapıldı. Ardından veri tabanında bulunan tablolara uygun veri girişleri için bir konsol uygulaması yapıldı. Bu uygulamada kullanıcı veri tabanına yeni "Kategori Ekleme", "Ürün Ekleme", "Ürün Listeleme", "Ürün Silme" veya "Ürün Güncelleme" işlemleri yapabilmektedir.

---

📌 **Proje 11 (cSharpEgitimKampi301.EntitiyLayer): OOP Modülü: C# ile N Katmanlı Mimari Entity Layer**  

Bu projede veri tabanımızda bulunacak tablolar ve içerisindeki sütunlar belirlendi ve oluşturuldu.

---

📌 **Proje 12 (cSharpEgitimKampi301.DataAccessLayer): OOP Modülü: Data Access Katmanı ve Context Sınıfı**  

Bu projede öncelikle bir önceki projede oluşturduğumuz tabloları birbirleriyle ilişkilendirme işlemi yapıldı. Ardından oluşturulan projelere 'reference' ekleme yapıldı. AppConfig kısmından MSSQL bağlantısı yapıldı.

---
📌 **Proje 13 : OOP Modülü - Migration İşlemleri ve Abstract Interfacele**  

Bu projede DataAccessLayer içinde daha önce oluşturduğumuz 'Abstract' klasörüne yeni 'Interface'ler eklendi. Bu oluşturduğumuz 'Interface'ler veri tabanımızda bulunan tablolara ekleme,silme, güncelleme işlemleri için bağlantı sağlandı.

---
📌 **Proje 14 : Orm Yapısı - Entity Framework DbFirst ve Model Oluşturma**

Bu projede MSSQQL üzerinden yeni bir veri tabanı oluşturup tabloları ve sütunları ayarlandı. Ardından VSCode'da yeni bir proje açıldı ve içerisine ADO.NET Entity Data Model eklendi ve MSSQL'de oluşturulan veri tabanı bağlantısı yapıldı. 

---
📌 **Proje 15 : Entity Framework Metotları ile Proje Uygulaması**

Bu projede MSSQL üzerinde ilk önce Admin tablosu oluşturuldu. Ardından form ekranına gerekli 'Toolbox'lar eklendi. Kullanıcıları listeleme, yeni kullanıcı ekleme,silme,güncellemei getirme işlemleri yapıldı.

---
📌 **Proje 16 : Entity Framework - Tur Projesi Location İşlemleri**

Bu projede MSSQL'de oluşturduğumuz tablolaradan biri olan 'Location' tablosunun form ekranı hazırlandı ve listeleme, ekleme, silme, güncelleme işlemleri yapıldı.

---
📌 **Proje 17 : Entity Framework - Tur Projesi Statistics Form Ekranı Projesi**

![Ekran görüntüsü 2024-12-13 170537](https://github.com/user-attachments/assets/7d3c56d0-41f5-4ef5-ac3b-803915859219)

Bu C# Windows Forms uygulaması, FrmStatistics formunda bir veri tabanından çeşitli istatistikleri görüntülemeyi amaçlayan bir yapıyı içeriyor. Form yüklendiğinde (FrmStatistics_Load metodu), veritabanından farklı sorgularla veri çekilerek çeşitli istatistikler hesaplanır ve etiketlere (Label) aktarılır. Örneğin, toplam lokasyon sayısı, kapasite toplamı, rehber sayısı, en yüksek kapasiteye sahip lokasyon, en yüksek fiyatlı lokasyon gibi veriler hesaplanır ve kullanıcıya gösterilir. 

---
📌 **Proje 18 : EntityState Komutları, Generic Repository Sınıfı ve Ef Sınıfları**

Bu projede, Generic Repostory yapısını kurduk. EntityFramework klasörünün classları ayarlandı.

---
📌 **Proje 19 :  Business Katmanı ve Logic Kurallar**

Bu projede, Business Layer içindeki Abstarct'lara miras alma işlemleri yapıldı. Concrete içine sınıflar oluşturuldu. Constructor yapıcı metot oluşturuldu. Presentation Layer içinde ' FrmCategory' adında yeni bir form ekranı açıldı ve içerisinde kullanılacak olan toolbox'lar eklendi. 

---
📌 **Proje 20 :  Dependency Injection**

Bu projede, 'Business Layer' içindeki 'OrderManager ve ProductManager' kısımlarında gerekli kodlar yazıldı.
'Presentation Layer' kısmında bulunan 'FrmCategory' form ekranı için veri tabanında veri girişleri yapıldı. Ardından formdaki butonların kodları yazıldı.

---
📌 **Proje 21 :  Entitye Özgü Metot Yazmak**

Bu projede, 'Presentation Layer' içine 'FrmProduct' adında form ekranı eklendi ve içeriği düzenlendi. Daha sonra veri tabanından listeleme işlemi gerçekleştirildi.

---
📌 **Proje 22 :  C# ile Dapper Kullanımı**

Bu projede, 301 modülünde bulunan Presentation Layer'da FrmProduct kısmının kalan buton kodları yazıldı. Ardından 501 modülü için yeni bir form ekranı oluşturuldu ve gerekli araçlar eklendi. 'Dtos' klasörü oluşturarak SQL'den gelen tablomuzun özelliklerini tutmamıza yaracak olan kodlar yazıldı. Oluşturulan 'Repositories' klasöründe de gerekli class'lar eklendi ve kodlar yazıldı.

---
📌 **Proje 23 :  Dapper İşlemlerinin Tamamlanması**

![1](https://github.com/user-attachments/assets/40d7778b-0a01-457f-af2e-00861de44bad)

Bu projede bir önceki Dapper işlemlerinin devamı yapıldı. Oluşturulan Form ekranında bulunan butonların kodları yazıldı ve aktif çalışır hale getirildi.

---
📌 **Proje 24 :  C# ile MongoDb Kullanımı 1**

![Ekran görüntüsü 2024-12-26 172547](https://github.com/user-attachments/assets/279d9032-a2e2-4766-9a91-ec6bedcb7219)

Bu projede 601 modülüne geçildi ve yeni bir proje oluşturuldu. Yeni projede yeni bir form ekranı ve bu form ekranına 'label, toolbox, button'lar eklendi. MongoDB bağlantısı yapıldı ve tablo oluşturuldu. 

---
📌 **Proje 25 :  C# ile MongoDb Kullanımı 2**

![Ekran görüntüsü 2024-12-30 184730](https://github.com/user-attachments/assets/7da087d6-8c53-40c3-90ab-bdeba91ae117)

Bu projede, oluşturduğumuz 'CustomerOperations' sınıfına "Listele, Sil, Güncelle ve ID'ye Göre Getir" işlemlerininiz kodları yazıldı. Daha sonra Form ekranının kod kısmında butonların özellikleri "CustomerOperations'dan" çağrılıp çalışır hale getirildi.

---
📌 **Proje 26 :   C# ile PostgreSQL Kullanımı 1**
![Ekran görüntüsü 2025-01-02 145016](https://github.com/user-attachments/assets/a7f423ac-0d7e-450f-a774-15b0bd4b73a6)
![Ekran görüntüsü 2025-01-02 145004](https://github.com/user-attachments/assets/e6ba3c84-e5ff-4b8a-9b4d-d787403cd1d8)

Bu projede 'FrmCustomers' adında yeni bir form ekranı açarak PostgreSQL ile birlikte kullanıcı tablosu oluşturuldu. Bu kullanıcı tablosu sayesinde PostgreSQL'de oluşturulan tabloya kullanıcı ekleme, silme ve bu kullanıcının bilgilerini güncelleme' özellikleri eklendi.


---
📌 **Proje 27 :   C# ile PostgreSQL Kullanımı 2**

![Ekran görüntüsü 2025-01-03 215751](https://github.com/user-attachments/assets/996c517e-ec6c-42c7-b120-131f5c612153)
![Ekran görüntüsü 2025-01-03 215838](https://github.com/user-attachments/assets/417a5de5-9c63-4f40-9996-906155c07c9d)


Bu projede 'FrmDepartment' ve 'FrmEmployee' adında iki tane yeni form ekranı açarak PostgreSQL ile birlikte 'Departments ve Employees' tabloları oluşturuldu. Bu 'Departments' tablosuna veri girişleri yapıldı ve 'FrmEmployee' ekranında eklenen departmantlar 'ComboBox' ile çekildi. 'FrmEmployee' ekranında yeni çalışan ekleme işlemleri yapıldı.


---
Bu projeler, C# dilindeki temel konulara hakimiyet kazanmak ve yazılım geliştirme becerilerimi geliştirmek için oldukça faydalı oldu. 😊  
