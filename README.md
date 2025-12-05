# Titanic Machine Learning Project

Bu proje, Kaggle’daki **Titanic: Machine Learning from Disaster** yarışması için hazırlanmıştır.  
Amacımız, Titanic kazasında yolcuların **hayatta kalıp kalmayacağını tahmin etmek**.

---

## 📂 Dosyalar

- `train.csv` → Eğitim verisi (hayatta kalma bilgisi var)
- `test.csv` → Test verisi (hayatta kalma bilgisi yok, model tahmin edecek)
- `submission.csv` → Kaggle’a yüklemek için tahmin dosyası
- `titanic_colab_notebook.ipynb` → Colab notebook ile tüm adımlar

---

## 📝 Adımlar

1. **Veri Okuma:** `train.csv` ve `test.csv` dosyalarını pandas ile oku
2. **Eksik Verileri Doldurma:** Age, Fare ve Embarked sütunlarındaki boş değerleri doldur
3. **Kategorik Verileri Sayıya Çevirme:** Sex ve Embarked gibi yazıları sayıya çevir
4. **Modeli Hazırlama:** Logistic Regression kullan
5. **Eğitim ve Doğrulama Verilerini Ayırma:** Train-test split ile veriyi ayır
6. **Model Eğitme ve Tahmin:** Modeli eğitim verisi ile eğit, doğrulama verisi ile test et
7. **Test Verisi Tahmini:** Test verisi için tahmin yap ve `submission.csv` dosyası oluştur
8. **Kaggle’a Yükleme:** `submission.csv` dosyasını yarışmaya gönder

---

## 📊 Kullanılan Kütüphaneler

- `pandas` → Veri okuma ve tablo işlemleri  
- `numpy` → Sayısal hesaplamalar  
- `sklearn` → Modelleme ve doğrulama  
- `LogisticRegression` → Basit tahmin modeli  
- `accuracy_score` → Doğruluk ölçümü

---

## ⚡ Notlar

- Daha iyi sonuç için Random Forest veya XGBoost kullanılabilir, özellik mühendisliği yapılabilir.
