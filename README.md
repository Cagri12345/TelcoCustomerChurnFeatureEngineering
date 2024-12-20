# Telco Müşteri Kaybı Analizi ve Özellik Mühendisliği

Bu proje, telco müşteri kaybını (churn) tahmin etmek için veri ön işleme, özellik mühendisliği ve makine öğrenimi modellerinin uygulanmasını kapsamaktadır. Telco müşteri verileri kullanılarak çeşitli analizler yapılmış ve tahmin modelleri oluşturulmuştur.

## Proje Amaçları
- Müşteri kaybını etkileyen faktörleri belirlemek.
- Çeşitli makine öğrenimi modelleriyle müşteri kaybını tahmin etmek.

## Veri Seti
Proje, [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) verisi ile gerçekleştirilmiştir. Bu veri seti müşteri bilgileri, hizmet türleri ve ödeme detaylarını içermektedir.

- **Satır Sayısı:** 7043
- **Sütun Sayısı:** 21
- **Öne Çıkan Sütunlar:**
  - `customerID`: Müşteri kimliği
  - `gender`: Cinsiyet
  - `SeniorCitizen`: Yaşlı müşteri durumu
  - `tenure`: Hizmet alma süresi (ay olarak)
  - `MonthlyCharges`: Aylık ödeme tutarı
  - `TotalCharges`: Toplam ödeme tutarı
  - `Churn`: Müşteri kaybı durumu (Evet/Hayır)

## Kullanılan Yöntemler
- **Veri Ön İşleme:**
  - Eksik değerlerin kontrol edilmesi ve temizlenmesi.
  - Veri dönüşümü ve normalizasyon.
- **Özellik Mühendisliği:**
  - Yeni özelliklerin türetilmesi.
  - Etkisiz özelliklerin çıkarılması.
- **Makine Öğrenimi Modelleri:**
  - Lojistik Regresyon
  - Karar Ağaçları (Decision Trees)
  - Random Forest
  - Gradient Boosting
