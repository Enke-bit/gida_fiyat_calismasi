# Veri Analizi ve Tahmin Projesi

Bu proje, bir veri setindeki Period ve Data_value değerlerini analiz etmeyi ve tahmin etmeyi amaçlar. Aşağıdaki adımlar ve görselleştirmeler, veri setinin içeriğini anlamak ve tahmin modelinin performansını değerlendirmek için kullanılmıştır.

## Veri Seti
Veri seti şu sütunları içerir:

- Series_reference: Seri referansı
- Period: Zaman periyodu
- Data_value: Veri değeri
- STATUS: Durum
- UNITS: Birimler
- Subject: Konu
- Group: Grup
- Series_title_1: Seri başlığı

## Örnek veri:

Series_reference    CPIM.SE903
Period              1960.03
Data_value          45.116296
STATUS              FINAL
UNITS               Index
Subject             Consumers Price Index - CPI
Group               Food Price Index for New Zealand
Series_title_1      Food


## Görselleştirmeler
Proje, veri setindeki Period ve Data_value değerlerini analiz eden çeşitli görselleştirmeleri içerir.

## Makine Öğrenmesi Modeli
Proje kapsamında bir Karar Ağaçları (Decision Tree) regresyon modeli kullanılmıştır. Model, belirli bir Period için Data_value tahmini yapmak amacıyla eğitilmiştir.

## Sonuç
Proje, Period ve Data_value arasındaki ilişkiyi analiz ederek ve bir tahmin modeli kullanarak veri değerlerini tahmin etmeyi başarmıştır. Görselleştirmeler, modelin performansını ve gerçek değerlerle tahmin edilen değerler arasındaki farkları görsel olarak anlamamıza yardımcı olur.


## Katkıda Bulunanlar
İbrahim Püsküllü - Proje kurucusu ve geliştirici
## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

