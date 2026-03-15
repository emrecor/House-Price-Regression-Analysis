# 🏠 House Prices: Advanced Regression Techniques (Kaggle)

Bu proje, Kaggle'ın popüler "House Prices" yarışması için geliştirdiğim kapsamlı bir veri analizi ve makine öğrenmesi çalışmasıdır. Amacımız, evin çeşitli özelliklerini (metrekare, oda sayısı, konumu vb.) kullanarak satış fiyatını en düşük hata payıyla tahmin etmektir.

## 📊 Proje Özeti
- **Veri Seti:** 79 farklı değişken içeren konut özelliklerini kapsar.
- **Hedef:** Evlerin satış fiyatlarını (SalePrice) tahmin etmek.
- **Yöntemler:** Exploratory Data Analysis (EDA), Feature Engineering, Hyperparameter Optimization.

## 🛠️ Kullanılan Teknolojiler
- **Kütüphaneler:** Pandas, NumPy, Scikit-learn, XGBoost, CatBoost.
- **Optimizasyon:** Optuna (Hiperparametre tünelleme için).
- **Görselleştirme:** Matplotlib, Seaborn.

## 🚀 Öne Çıkan Adımlar
1. **Missing Value Management:** Eksik veriler, değişkenin türüne göre (mod, medyan veya 'None') dolduruldu.
2. **Feature Engineering:** Sayısal değişkenlerin veri tipleri optimize edildi ve model için yeni özellikler oluşturuldu.
3. **Modeling:** CatBoost ve XGBoost modelleri kullanılarak başarılı tahminleme yapıldı.
4. **Optimization:** Optuna kütüphanesi ile modellerin parametreleri en iyi performansı verecek şekilde ayarlandı.

## 📈 Sonuçlar
Notebook üzerinde yapılan çapraz doğrulama (cross-validation) sonuçlarına göre:
- **CatBoost RMSE:** ~1.126
- **XGBoost RMSE:** ~1.126
*(Not: Logaritmik dönüşüm yapıldıysa bunu belirtin)*
