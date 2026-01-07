# Titanic Veri Analizi Projesi

> Titanic kazasında yolcuların hayatta kalma oranlarını analiz eden kapsamlı bir veri bilimi projesi

## 📋 İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Veri Seti](#veri-seti)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Bulgular](#bulgular)
- [Teknolojiler](#teknolojiler)

## 📊 Proje Hakkında

Bu proje, Titanic kazasında yolcuların hayatta kalma oranlarını çeşitli faktörlere (yolcu sınıfı, cinsiyet, yaş vb.) göre analiz etmektedir. 

**Amaçlar:**
- Sosyo-ekonomik faktörlerin hayatta kalma üzerindeki etkisini incelemek
- Veri görselleştirme tekniklerini uygulamak
- Temel veri analizi becerilerini geliştirmek

## 📁 Veri Seti

**Kaynak:** Titanic Dataset (UCI Machine Learning Repository)  
**Dosya:** `data/titanic.csv`  
**Boyut:** ~900 gözlem, 12 özellik

**Özellikler:**
- `PassengerId`: Yolcu ID'si
- `Survived`: Hayatta kalma durumu (0=Hayır, 1=Evet)
- `Pclass`: Yolcu sınıfı (1, 2, 3)
- `Sex`: Cinsiyet
- `Age`: Yaş
- `SibSp`: Gemi üstündeki kardeş/eş sayısı
- `Parch`: Gemi üstündeki ebeveyn/çocuk sayısı
- `Fare`: Bilet ücreti
- `Embarked`: Biniş limanı

## 🚀 Kurulum

### Gereksinimler
- Python 3.8+
- pip

### Adımlar

1. **Depoyu klonlayın:**
```bash
git clone https://github.com/yourusername/titanic-analysis.git
cd titanic-analysis
```

2. **Sanal ortam oluşturun:**
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# veya
venv\Scripts\activate  # Windows
```

3. **Gerekli paketleri yükleyin:**
```bash
pip install -r requirements.txt
```

4. **Jupyter ortamını başlatın:**
```bash
jupyter lab
```

## 📖 Kullanım

Analizi çalıştırmak için:

```bash
# Jupyter Lab'i açın
jupyter lab

# notebooks/ klasöründen titanic_analysis.ipynb dosyasını açın
# Tüm hücreleri sırasıyla çalıştırın (Shift + Enter)
```

## 📂 Proje Yapısı

```
titanic-analysis/
├── README.md                 # Bu dosya
├── requirements.txt          # Python bağımlılıkları
├── .gitignore               # Git'e eklenmeyen dosyalar
│
├── data/                    # Veri dosyaları
│   └── titanic.csv          # Titanic veri seti
│
├── notebooks/               # Jupyter Notebooks
│   └── titanic_analysis.ipynb
│
├── src/                     # Python modülleri (gelecekte)
│   └── __init__.py
│
└── outputs/                 # Çıktı dosyaları (grafikler, raporlar)
```

## 🔍 Bulgular

### Ana Çıkarımlar

1. **Sınıf ve Hayatta Kalma:**
   - 1. sınıf yolcuların hayatta kalma oranı ~62%
   - 3. sınıf yolcuların hayatta kalma oranı ~24%
   - **Sonuç:** Sosyo-ekonomik durum, hayatta kalmada kritik rol oynadı

2. **Yaş Dağılımı:**
   - Çoğu yolcu 20-40 yaş arasında
   - Genç yetişkinler ağırlıklı bir yolcu profili

3. **Cinsiyet Etkisi:**
   - Kadınların hayatta kalma oranı erkeklere göre daha yüksek
   - "Kadın ve çocuklar önce" ilkesinin uygulandığının göstergesi

## 🛠️ Teknolojiler

| Teknoloji | Versiyon | Kullanım |
|-----------|----------|----------|
| **pandas** | ≥2.0.0 | Veri işleme ve manipülasyon |
| **numpy** | ≥1.24.0 | Sayısal hesaplamalar |
| **matplotlib** | ≥3.7.0 | Statik görselleştirme |
| **seaborn** | ≥0.12.0 | İstatistiksel görselleştirme |
| **scikit-learn** | ≥1.3.0 | Machine learning algoritmaları |
| **jupyter** | ≥1.0.0 | İnteraktif analiz ortamı |


---

