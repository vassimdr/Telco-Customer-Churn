# Telco Müşteri Kaybı Tahmini

![Telekom](telekom.jpg)

Bu proje, bir telekom şirketi müşterilerinin hizmetten ayrılıp ayrılmayacaklarını tahmin etmek için makine öğrenmesi modelleri geliştirmeyi amaçlar. Veriler, Kaliforniya'daki 7043 müşteriye ait müşteri kaybı bilgilerini içerir.

## Görev 1: Keşifçi Veri Analizi

### Adım 1: Numerik ve Kategorik Değişkenler

Proje, veri setindeki sayısal ve kategorik değişkenleri tanımlar ve bu değişkenleri belirler.

### Adım 2: Düzenlemeler

Veri setinde tip hatası olan değişkenler düzeltilir ve gerekli dönüşümler yapılır. Özellikle, sayısal gibi görünen ancak kategorik olan değişkenler düzeltilir.

### Adım 3: Dağılım Analizi

Sayısal ve kategorik değişkenlerin veri içindeki dağılımı incelenir. Temel istatistiksel ölçümler ve frekans analizi kullanılır.

### Adım 4: Kategorik Değişkenler ile Hedef Değişken İncelemesi

Kategorik değişkenlerin hedef değişkenle ilişkisi incelenir. Çapraz tablolar ve normalize edilmiş frekans analizi kullanılır.

### Adım 5: Aykırı Gözlem Analizi

Aykırı gözlemler tespit edilir ve görselleştirilir. Kutu grafikleri ve z-skor analizi kullanılır.

### Adım 6: Eksik Gözlem Analizi

Veri setindeki eksik gözlemler tespit edilir ve ele alınır. Eksik veriler doldurulur veya çıkarılır.

## Görev 2: Feature Engineering

### Adım 1: Eksik ve Aykırı Gözlemler

Eksik ve aykırı gözlemler için gerekli işlemler yapılır. Veri temizlenir ve düzeltilir.

### Adım 2: Yeni Değişkenler

Yeni özellikler ve değişkenler oluşturulur. Bu yeni özellikler modelin daha iyi performans göstermesine yardımcı olur.

### Adım 3: Encoding

Kategorik değişkenler sayısal verilere dönüştürülür. Bu, makine öğrenimi modellerinin kullanılabilirliğini artırır.

### Adım 4: Standartlaştırma

Numerik değişkenler standartlaştırılır. Değişkenlerin ölçekleri aynı hale getirilir.

## Görev 3: Modelleme

### Adım 1: Sınıflandırma Modelleri

Çeşitli sınıflandırma algoritmaları kullanılarak modeller oluşturulur. Bu modeller müşteri kaybını tahmin etmek için kullanılır ve doğruluk (accuracy) skorları incelenir.

### Adım 2: Hiperparametre Optimizasyonu

En iyi dört model seçilir ve bu modellerin hiperparametreleri optimize edilir. En iyi parametrelerle model tekrar kurulur.
