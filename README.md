<div id="top"></div>

![kisspng-microsoft-sql-server-mysql-database-logo-5b098c6ee92a46 0488681015273524309551](https://user-images.githubusercontent.com/74763030/150372747-19fd593e-232f-4cd0-80a9-76ff6db351bc.png )

## Hazırlayanlar -->

Burak KODALOĞLU <br>
Emre ARDIÇOĞLU <br>
Barış TURGUT <br>
Batın SEZER <br>
Erdem GENÇ <br>
Serhat KAHRAMAN <br>
Ahmet Yiğit UYSAL <br>
Umut CAN <br>
Efe VARDALI <br>

<p align="right">(<a href="#top">Başa geri dön</a>)</p>

## Sayfalar Hakkında Bilgiler -->

### Anasayfa: <br>

<br>

### Haberler: <br>

<br>

### Çalışanlar: <br>



### Kodsal içerik <br>

Controller : BankaController ve HomeController adında 2 tane controller olusturduk. <br>
            - BankaController icerisinde Ekle,Sil,Guncelle,Detay,Listele işlemlerini yaptırmak icin gerekli metodlar ve işlemler yaptık.<br>
             <br>
                      
Models : Banka.cs , Sube.cs ve ErrorViewModel adinda 3 tane Models olusturduk.
        - Banka.cs in altında ki class'in icini doldurduk.
        - Sube.cs in altında ki class'in icini doldurduk.
        - Buradaki oluşturduğumuz verileri SQL icinde tablo oluşturarak kullandık.
        
NhibernateHelper : NHibernate.cs
            -  NHibernate : .Net ortamı için hazırlanmış Orm dir.  Database de bulunan her bir tablonun bilgilerini almamıza yardımcı oldu.

Views : Banka , Home
       Banka : altinda Ekle,Sil,Guncelle,Detay,Listele adında ilgili alanlari görünteleme işlemleri yaptık.
              - Banka = Calısanlar
       Home : altinda Index , Privacy icerisine AnaSayfa yı ve Haberleri görüntüleyen kodları yazdık. 
              - Index = AnaSayfa
              - Privacy = Haberler
              
              
SQL : 2 adet tablo olusturuldu.
      - Banka Table ve Sube Table
      - Banka : Id Ad Soyad Telefon SehirIlce Banka_Ad  
             - PRIMARY KEY : ID
      - Sube : Id Ad Soyad Telefon Banka_Ad Banka 
             - PRIMARY KEY : ID
             - FOREIGN KEY  : ALTER TABLE Sube WITH CHECK ADD CONSTRAINT [FK_Sube_Banka_id] FOREIGN KEY (Banka) REFERENCES Banka (Id)
<br>

<p align="right">(<a href="#top">Başa geri dön</a>)</p>

## Kaynak -->
* [StackOverFlow](https://stackoverflow.com/)
* [Youtube](https://Youtube.com/)
* [GitHub](https://github.com/)
* [Bootstrap](https://getbootstrap.com)
* [Microsoft](https://Microsoft.com)
* [MicrosoftSQL](https://docs.microsoft.com/en-us/sql/relational-databases/tables/tables?view=sql-server-ver15)

<p align="right">(<a href="#top">Başa geri dön</a>)</p>
