# Gradient Descent Ödevi
## Intro :
Bu ödevde, basit bir lineer regresyon modeli için gradient descent algoritmasını uygulamamız istendi. Verilen araba fiyat tahmini veri kümesini kullanarak, araba fiyatını tahmin etmek için bir model eğittik.
## Method :
Verileri pandas dataframe'ine yükledik;Eksik verileri ortalama ile doldurduk;"brand" sütununu one-hot encoding ile sayısal hale dönüştürdük. X_train ve y_train'i ayırdık. predict, compute_cost, update_weights fonksiyonlarını oluşturduk. learning_rate değerini belirledik. Gradient descent algoritmasını 1000 iterasyon boyunca çalıştırdık. Son iterasyondaki w ve b değerlerini yazdırdık
## Results :
Elde edilen modelin doğruluğu %75 civarındaydı.
Farklı öğrenme oranları denedik ve en iyi sonucu 0.01 öğrenme oranı ile elde ettik.
Modelin hata fonksiyonu, eğitim sırasında azaldı.
## Discussion :
Gradient descent, basit bir lineer regresyon modeli eğitmek için etkili bir algoritmadır.
Öğrenme oranı, algoritmanın performansını önemli ölçüde etkileyebilir.
Daha fazla veri ve özellik kullanarak modelin doğruluğunu artırmak mümkündür.
