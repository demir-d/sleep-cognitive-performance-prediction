# Sleep Cognitive Performance Prediction

Bu proje, bireylerin uyku düzeni, yaşam alışkanlıkları ve günlük durumlarına ait verileri kullanarak bilişsel performans skorunu tahmin etmek amacıyla geliştirilmiştir.

## Problem Tanımı

Yarışma kapsamında katılımcılardan, verilen eğitim verisi üzerinden değişkenler arasındaki ilişkileri öğrenerek test verisi üzerindeki bireylerin bilişsel performans skorlarını tahmin etmeleri beklenmiştir.

Problem türü bir regresyon problemidir.

## Kullanılan Yöntemler

- Veri ön işleme
- Eksik değer doldurma
- Feature engineering
- Kategorik değişken yönetimi
- CatBoostRegressor modeli

## Veri Ön İşleme

Eksik sayısal değerler median yöntemi ile doldurulmuştur.

Eksik kategorik değerler "Bilinmiyor" etiketi ile tamamlanmıştır.

## Oluşturulan Özellikler

- uyku_kalitesi
- uyku_bozulma_skoru
- ekran_kafein_etkisi

## Kullanılan Model

Projede CatBoostRegressor modeli kullanılmıştır.

## Validation Sonucu

RMSE Skoru:

1.2236

## Çıktı Dosyası

Model tahminleri `submission.csv` dosyası olarak oluşturulmuştur.

## Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
