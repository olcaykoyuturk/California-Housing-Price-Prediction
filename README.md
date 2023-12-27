# California Ev Fiyat Tahmini Projesi

Bu proje, California'da bulunan ev fiyatlarını tahmin etmek amacıyla geliştirilmiştir. Veri bilimi ve makine öğrenimi yöntemleri kullanılarak oluşturulan bu projenin detayları aşağıda yer almaktadır.

## Veri Seti

Proje, California'daki evlere ait çeşitli özellikleri içeren bir veri seti kullanmaktadır. Bu özellikler arasında coğrafi konum, ev özellikleri, nüfus istatistikleri ve gelir seviyeleri bulunmaktadır. Veri seti, [housing.csv](housing.csv) dosyasından yüklenmektedir.

## Veri Ön İşleme

Proje, veri setindeki eksik değerleri kontrol edip, eksik değerleri uygun şekilde doldurarak veriyi temizlemektedir. Ayrıca, kategorik verilerin sayısal değerlere dönüştürülmesi için Label Encoder kullanılmaktadır.

## Veri Görselleştirme

Proje, veri setindeki ilişkileri anlamak için Seaborn kütüphanesini kullanarak bir ısı haritası (heat map) oluşturmaktadır. Bu harita, bağımlı ve bağımsız değişkenler arasındaki ilişkileri görselleştirmektedir.

## Model Eğitimi

Proje, veriyi eğitim ve test setlerine bölmekte ve ardından hem Lineer Regresyon hem de Random Forest Regresyon modelleri ile eğitim gerçekleştirmektedir. Her iki modelin başarı oranları da R-squared metriği kullanılarak değerlendirilmektedir.

## Sonuçlar

- Lineer Regresyon Modeli: %44 doğruluk oranı.
- Random Forest Regresyon Modeli: %63 doğruluk oranı.

## Kullanım

Projenin kullanımı oldukça basittir. İlgili Jupyter Notebook dosyasını çalıştırarak modelleri eğitebilir ve ev fiyatları için tahminlerde bulunabilirsiniz.
