# -womenintech_python_bitirme_projesi-


![16](https://user-images.githubusercontent.com/80313913/202870967-de024f3c-1c71-41d8-9da5-f21bb4e46d1b.jpg)



Bu veri seti içerisinde; 1896 yılından 2016 yılına kadar olan olimpiyat oyunlarıyla ilgili, yarışmacının adı, cinsiyeti, yaşı, boyu, kilosu, yarıştığı spor dalı, kazandığı madalya gibi bilgiler bulunmaktadır. 

Veri setleri iki tane .csv dosyasından oluşmaktadır:

1-athletes.csv

2-NOC_regions.csv

athlete_events.csv dosyasında:

    271116 satır & 15 Sütun bulunur.
    Her bir satır sporcunun bilgilarini temsil eder. Bir sporcu birden fazla yarışta yarıştığı için duplicate veriler vardır.
    
        ID - Unique number for each athlete
        Name - Athlete's name
        Sex - M or F
        Age - Integer
        Height - In centimeters
        Weight - In kilograms
        Team - Team name
        NOC - National Olympic Committee 3-letter code
        Games - Year and season
        Year - Integer
        Season - Summer or Winter
        City - Host city
        Sport - Sport
        Event - Event
        Medal - Gold, Silver, Bronze, or NA
        
  Age, Height, Weight ve Medal sütunlarında NaN değerler bulunmaktadır. Bu değerlerin Age, Height, Weight için girilmediğini düşündüm. Medal için ise madalya alamayan sporculara NaN denildiğini varsaydım.
  
  Data incelemesinde başlıca aşağıdaki analizleri yaptım:
  
  1- Yarışmacı profil analizleri: Age&Weight&Height İlişkilerinin incelenmesi
  
  2- Cinsiyetlere göre dağılımlar & Olimpiyatlarda Kadın yarışmacalar
  
  3- Ülkelere göre analizler
  
  4- Olimpiyatta Türkiye verilerinin incelenmesi 
  
  
  
  
  
  
