# ♻️ Atık Takas Sistemi – Yapay Zekâ Destekli Eşleştirme Platformu

Bu sistem, üretici ve alıcı firmalar arasında **endüstriyel simbiyoz** odaklı atık takasını kolaylaştırmak için geliştirilmiş **yapay zekâ destekli bir öneri sistemidir.**

---

## 🚀 Öne Çıkan Özellikler

- ✅ Atık & NACE kodu girişli kullanıcı arayüzü
- ✅ YSA (Yapay Sinir Ağı), XGBoost, ANFIS modelleriyle firma önerisi
- ✅ OpenRouteService API ile coğrafi mesafe entegrasyonu
- ✅ PF-AHP + TOPSIS ile çok kriterli karar analizi
- ✅ Kullanıcı girdisine göre özelleşmiş eşleşme
- ✅ Excel'e kayıt ve öneri geçmişi yönetimi

---

## 🔧 Kullanılan Teknolojiler

- Python
- Flask
- XGBoost / ANFIS / YSA (Keras / Tensorflow)
- OpenPyXL, Pandas, Numpy
- HTML, Bootstrap (arayüz)
- OpenRouteService (API)

---

## 🧠 Karar Kriterleri

- Karbon ayak izi
- Lojistik uygunluk
- Süreklilik
- Güven
- Kapasite
- Finansal uygunluk

---

## 🧪 Uygulama Akışı

1. Firma giriş ekranı: atık kodu + sektör bilgisi girilir
2. Üretim tahmini modülü çalışır
3. Kriterler alınır ve TOPSIS uygulanır
4. Uygun firmalar önerilir
5. Sonuçlar Excel’e kaydedilir

---

## 📂 Proje Yapısı

Atik-main/
├── app.py
├── tavsiye.py
├── templates/
│ └── index.html, giris.html, sonuc.html
├── static/
│ └── style.css
├── veriler/
│ └── guncellenmis_waste_detect.csv
├── modeller/
│ └── ysa_model.h5, label_encoder.pkl, anfis_model.npz


---

## 👩‍💻 Geliştiriciler

> **Büşra Mina AL**  > www.linkedin.com/in/bmi̇nal60135806

> Ve GreenCode ekibi


---

## 📜 Lisans

Bu proje özel lisanslıdır. Kullanım, dağıtım veya ticari amaçlı çoğaltım için geliştirici izni gereklidir
