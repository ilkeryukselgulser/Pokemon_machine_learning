# 🐉 Pokemon Legendary Prediction with Machine Learning

Bu proje, bir Pokemon'un istatistiklerine (HP, Atak, Savunma, Hız vb.) bakarak o Pokemon'un **"Legendary" (Efsanevi)** olup olmadığını tahmin eden bir makine öğrenmesi çalışmasıdır.

## 📊 Proje Hakkında
Bu çalışmada, yaklaşık 800 Pokemon'un verilerini içeren bir veri seti kullanılmıştır. Veri seti üzerinde keşifçi veri analizi (EDA) yapılmış, eksik veriler işlenmiş ve çeşitli sınıflandırma algoritmaları kullanılarak en yüksek doğruluk oranına sahip model seçilmiştir.

### Kullanılan Teknolojiler ve Kütüphaneler
* **Python 3.x**
* **Pandas & NumPy:** Veri işleme ve analizi.
* **Matplotlib & Seaborn:** Veri görselleştirme.
* **Scikit-Learn:** Makine öğrenmesi modelleri, veri ön işleme ve metrikler.

## 📈 Model Performansı
Proje kapsamında aşağıdaki algoritmalar denenmiştir:
* Random Forest Classifier
* Support Vector Machines (SVM)
* K-Nearest Neighbors (KNN)
* Logistic Regression
* Decision Tree

**En iyi sonuç veren model:** `Random Forest Classifier` (Yaklaşık %95+ doğruluk oranı).

## 🚀 Kurulum ve Çalıştırma
Projeyi kendi bilgisayarınızda çalıştırmak için:

1. Bu depoyu klonlayın:
   ```bash
   git clone [https://github.com/ilkeryukselgulser/Pokemon_machine_learning.git](https://github.com/ilkeryukselgulser/Pokemon_machine_learning.git)


   Gerekli kütüphaneleri yükleyin:

Bash

pip install pandas numpy matplotlib seaborn scikit-learn
Jupyter Notebook veya VS Code üzerinden pokemon_machine_learning.ipynb dosyasını açın ve hücreleri çalıştırın.

📂 Veri Seti Yapısı
Veri setinde yer alan temel sütunlar:

Name: Pokemon adı

Type 1 & Type 2: Pokemon tipleri

Total: İstatistiklerin toplamı

HP, Attack, Defense, Sp. Atk, Sp. Def, Speed: Temel savaş istatistikleri

Generation: Nesil bilgisi

Legendary: Hedef değişken (Efsanevi mi? True/False)

🎯 Sonuçlar
Model, özellikle yüksek "Total" puanına ve spesifik istatistik dağılımlarına sahip Pokemonları yüksek doğrulukla "Legendary" olarak sınıflandırabilmektedir. Notebook içerisinde yer alan Confusion Matrix ve Classification Report kısımlarından detaylı metrikleri inceleyebilirsiniz.

Geliştiren: ilkeryukselgulser


---

### Nasıl Eklenir?
1. Bilgisayarındaki proje klasörüne git.
2. Sağ tık -> **Yeni Metin Belgesi** oluştur ve adını `README.md` yap (sonundaki `.txt` uzantısını sildiğinden emin ol).
3. Yukarıdaki metni kopyalayıp bu dosyanın içine yapıştır ve kaydet.
4. Terminale (Git Bash) dönüp şu komutları yaz:
   ```bash
   git add README.md
   git commit -m "README dosyası eklendi"
   git push origin main
