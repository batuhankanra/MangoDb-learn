# BURASI MANGODB İÇİN KULLANACAĞIM KODLAR BÖLÜMÜ

- [use kutuphane] yazarak database geçiş yapabiliyoruz

- [db.kitaplar.insertOne({kitapAd:"kitapadı1",yazarAd:"yazar1"})] diyerek 1 tane ekleme yapabiliyoruz

- [db.kitaplar.insertMany({kitapAd:"kitap2",yazarAd:"yazar2"},{kitapAd:"kitap3",yazarAd:"yazar3"})] diyerek istediğimiz kadar ekleme yapabiliriz

- [db.kitaplar.find()] kitaplar document'tini direk hepsini karşımıza çıkarır

- [db.kitaplar.find({kitapAd:kitap1})] kitapAd'ın kitap1 satırını getirir sadece

- [db.kitaplar.filter(2)] kitaplar document'tinin 2 tanesini getirir

- [db.kitaplar.find().sort({puan:1})] puanların küçükten büyüğe sıralar

- [db.kitaplar.find().sort({puan:-1})] puanların büyükten küçüğe  sıralar


- [db.kitaplar.find().sort({kitapAd:1})] kitapAd A'dan Z'ye kadar sıralar

- [db.kitaplar.find().sort({kitapAd:-1})] kitapAd Z'den A'ya kadar sıralar
