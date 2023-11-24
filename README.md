# KUTUPHANELER
## ERCİYES TEKNOPARK SQL BOOTCAMP

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Erciyes Teknopark'ın ev sahipliğinde Techcareer ile birlikte düzenlenen SQL BOOTCAMP programında bitirme ödevi olarak hazırlanan veri tabanıdır.
Proje aşağıda ki isterler göz önüne alınarak hazırlanmıştır.


> • Birden fazla kütüphane yönetilebilecek.

> • Kütüphanelerin ve üyelerin adresleri tutulacak.

> • Hangi kütüphanede hangi kitabın kaç adet bulunduğu kayıt edilecek.

> • Kitapların kategorileri bulunacak ve kitapaların ısbn numarası, yayın tarihi ve sayfa sayısı ile birlikte tutulacak.

> • Üyelerin ismi, telefon numarası, cinsiyet ve e posta bilgilerini kayıt edilebilecek.

> • Yazarların ad ve soyadı tutulması yeterlidir.

> • Emanet olarak verilen kitaplar birbirinden karıştırılmayacak şekilde takip edilebilecek ve emanet verilen tarih ile teslim tarihi kayıt altına alınabilecek.

> • Yönetici, Personel ve Ziyaretçi konumunda üç adet kullanıcı olacak.
	Ziyaretçi kullanıcısı sadece kitapları görünütüleyebilecek.
	Personel kullanıcısı kütüphane DDL, DML komutlarını işleyebilecek
	Yönetici kullanıcısı bütün serveri kontrol edebileek.

## ER DİYAGRAMI
İsterler sonrsında ortaya çıkan ER Diyagramı:

![Er Diyagramı](https://raw.githubusercontent.com/MELIHKOCAK/SQLBOOTCAMP/main/ER%20D%C4%B0YAGRAM.png)
## TEKNOLOJİLER

Projemi geliştirirken kullandığım teknolojiler.

- [SSMS] - Sql Server Managment Studio 2019
- [SQLENGİNE] - SQL Server(Database Engine)

## YÜKLEME

Yukarıda bağlantıda verilen iki dosyayı indirip kurduktan sonra projenin klonlayalım.

```sh
git clone https://github.com/MELIHKOCAK/SQLBOOTCAMP
```
Projenenin içinde ki "Script" isimli "sql" uzantılı dosyayı çalıştıralım.
```sh
Script.sql
```
(Eğer SSMS programını doğru kurulduysa "sql" uzantılı dosyalar bu program ile açılacaktır.)

SSMS programı ilk açıldığında servere bağlantı isteyecektir. Program kurulurken bir hata ile karşılaşılmadıysa ```Connect ``` butonuna tıklayarak giriş yapabiliriz.

Giriş işlemimiz tamamladıktan sonra klavyemizde ```F5``` tuşuna basarak projemizi ```execute``` etmiş oluruz. Bu aşamadan sonra kurulum işlemimiz tamamlanmış olur. ```Object Explorer```pencresinden veri tabanımızı ve ona ait objelerimizi görüntüleyebiliriz.


   [SSMS]: <https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16>
   [SQLENGİNE]: <https://www.microsoft.com/en-us/sql-server/sql-server-2019>

