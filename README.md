# Titanic - Machine Learning from Disaster 

Bu proje, Kaggle üzerindeki ünlü Titanic veri seti kullanılarak geliştirilmiş bir başlangıç seviyesi Makine Öğrenmesi projesidir.

##  Projenin Amacı
Titanic yolcularının yaş, cinsiyet, bilet sınıfı gibi özelliklerini kullanarak hayatta kalıp kalamayacaklarını tahmin eden bir model geliştirmek.

## Kullanılan Teknolojiler
* **Python**
* **Pandas & NumPy:** Veri analizi ve manipülasyonu için.
* **Scikit-learn:** Makine öğrenmesi modelleri (Random Forest) için.

##  Neler Yaptım?
1. **Veri Analizi (EDA):** Kadınların ve 1. sınıf yolcuların hayatta kalma oranının daha yüksek olduğunu gözlemledim.
2. **Eksik Veri Doldurma:** 'Age' sütunundaki eksik verileri ortalama ile doldurdum.
3. **Feature Engineering:** * İsimlerden 'Title' (Mr, Mrs, Master vb.) bilgisini çıkardım.
    * Aile boyutunu hesapladım.
4. **Modelleme:** Random Forest algoritması kullandım ve parametre optimizasyonu yaptım.

##  Sonuç
Kaggle test setinde **%77.5** doğruluk (accuracy) oranına ulaştım.
