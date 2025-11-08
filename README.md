# ♻️ Atık Takas Sistemi – Yapay Zekâ Destekli Eşleştirme Platformu

**Atık Takas Sistemi**, üretici ve alıcı firmalar arasında endüstriyel simbiyoz yoluyla **atıkların yeniden kullanımını** optimize eden, **çok kriterli karar destek ve yapay zekâ tabanlı eşleştirme** altyapısına sahip bir platformdur.

> Sürdürülebilir üretim için: Atık, artık atık değil; **yeni bir kaynaktır.**

---

## 🚀 Öne Çıkan Özellikler

- ✅ Atık & NACE kodu giriş arayüzü
- ✅ YSA (ANN), XGBoost ve **ANFIS** tabanlı firma öneri sistemi
- ✅ **PF-AHP + TOPSIS** ile çok kriterli karar analizi
- ✅ **OpenRouteService API** ile coğrafi mesafe hesaplama
- ✅ Kullanıcı girdilerine göre dinamik eşleşme önerileri
- ✅ Öneri sonuçlarını **Excel’e kaydetme & geçmiş yönetimi**

---

## 🔧 Kullanılan Teknolojiler

| Bileşen | Açıklama |
|--------|---------|
| Python | İş mantığı ve veri işleme |
| Flask | Web arayüzü ve routing |
| XGBoost / ANFIS / YSA | Firma öneri modelleri |
| Pandas / Numpy / OpenPyXL | Veri işleme ve Excel yönetimi |
| OpenRouteService API | Coğrafi mesafe değerlendirme |
| TOPSIS + PF-AHP | Çok kriterli karar desteği |
| HTML + Bootstrap | Ön yüz tasarımı |

---

## 🧠 Karar Kriterleri (TOPSIS Girdileri)

- Karbon ayak izi etkisi
- Lojistik uygunluk
- Tedarik sürekliliği
- Kurumsal güven
- Kapasite yeterliliği
- Finansal maliyet-etkinlik oranı

---

## 🧪 Uygulama Akışı

1. Firma atık kodu & sektör bilgisi girer
2. Sistem uygun dönüşüm/yeniden kullanım eşlerini filtreler
3. Yapay zekâ modelleri benzer firma eşleşmelerini tahmin eder
4. Çok kriterli analiz uygulanır (PF-AHP → TOPSIS)
5. Uygun firmalar **puanlanmış öneri listesi** olarak kullanıcıya sunulur
6. Sonuçlar Excel’e kaydedilir ve geçmişe işlenir

---

## 📂 Proje Dosya Yapısı

```
Atik-main/
│
├── app.py                       # Flask ana sunucu
├── tavsiye.py                   # Model + TOPSIS + öneri iş mantığı
│
├── templates/
│   ├── index.html               # Giriş
│   ├── giris.html               # Firma bilgi ekranı
│   └── sonuc.html               # Öneri çıktıları
│
├── static/
│   └── style.css                # Arayüz stilleri
│
├── veriler/
│   └── guncellenmis_waste_detect.csv   # Atık-tür veri tabanı
│
└── modeller/
    ├── ysa_model.h5             # Yapay Sinir Ağı modeli
    ├── anfis_model.npz          # ANFIS modeli parametreleri
    └── label_encoder.pkl        # Kategorik kod çözücü
```

---

## 👩‍💻 Geliştiriciler

**Büşra Mina AL**  
Yapay Zekâ & Endüstri Mühendisi  
LinkedIn: https://www.linkedin.com/in/bmi̇nal60135806

**Ve GreenCode Ekibi**

---

## 📜 Lisans

```
Bu proje özel lisanslıdır.
İzin alınmaksızın:
- Kopyalanamaz
- Dağıtılamaz
- Ticari amaçla kullanılamaz
- Türetilmiş versiyonları oluşturulamaz

İhlaller hukuki takibe tabidir.
```
