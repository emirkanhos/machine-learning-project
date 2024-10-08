# Kaggle

[Kaggle Gitmek İçin Tıklayınız](https://www.kaggle.com/code/emirkanhos/proje)

colabde çalıştırdım bütün satırları fakat kaggleda çok uzun sürdü çalıştırmam son satırları çalıştıramadım tekrar denemeye çalışıyorum 12den sonrasına yetişebilir ancak

# Makine Öğrenmesi ile Araç Satış Verileri

# Projenin Amacı

Bu projenin amacı araç satış verileri üzerinden farklı makine öğrenme algoritmalarını test edip en uygun modeli  geliştirmektir. Proje en doğru sonuçları elde edebilmek için çeşitli modelleri karşılaştırarak en iyi performansı veren algoritmayı seçmeyi hedefler.

# Veri Seti

Kullanılan dataset, 558838 satırdan oluşmaktadır. Sütun isimleri ise sırasıyla şu şekildedir: 

 ***make:*** Aracın markası
 
 ***model:*** Aracın modeli
 
 ***trim:*** Aracın donanım seviyesi
 
 ***body:*** Aracın kasa tipi
 
 ***transmission:*** Aracın şanzıman türü
 
 ***vin:*** Aracın benzersiz kimlik numarası
 
 ***state:*** Aracın satışının gerçekleştiği eyalet
 
 ***color:*** Aracın dış rengi
 
 ***interior:*** Aracın iç mekan rengi
 
 ***seller:*** Aracı satan kişi
 
 ***saledate:*** Aracın satış tarihi
 
 ***sellingprice:*** Aracın satış fiyatı
 
 ***year:*** Aracın üretim yılı
 
 ***mileage:*** Aracın kilometre bilgisi
 
 ***car_age:*** Aracın yaşı

# Değişkenler
Bağımsız değişkenler(x)

***make:*** Aracın markası
***model:*** Aracın modeli
***trim:*** Aracın donanım seviyesi
***body:*** Aracın kasa tipi
***transmission:*** Aracın şanzıman türü
***vin:*** Aracın kimlik numarası -- Analize dahil edilmemiştir
***state:*** Aracın satışının yapıldığı eyalet
***color:*** Aracın dış rengi
***interior:*** Aracın iç renk seçimi
***seller:*** Satıcı bilgisi
***saledate:*** Satış tarihi
***year:*** Aracın üretim yılı
***mileage:*** Aracın kat ettiği mesafe (kilometre)
***car_age:*** Aracın yaşı

Bağımlı değişkenler(y) 

***sellingprice:*** Aracın satış fiyatı

Bu projede kullanılan algoritmalar:

***Random Forest Regressor***

***Linear Regression***

***Decision Tree Regressor***

***K-Means*** 

***RandomizedSearchCV***

# Model Seçimi 
Bu projede çeşitli makine öğrenmesi algoritmalarını deneyerek araç satış verilerinden en doğru tahmin sonucunu bulmayı amaçladım. Algoritmalar arasında Random Forest, Linear Regresyon, ve Decision Tree gibi modellerini test ettim. Her modelin performanslarını karşılaştırdıktan sonra en iyi sonucu veren Random forest modelini seçtim. Daha da iyileştirmek için hiperparametre optimizasyonu yaptım. Sonuç olarak hiperparametre ve model değerlendirmesi yaparak doğruluklarını ölçtüm.


# Sonuç

Bu projede araç satış fiyatlarını tahmin etmek için makine öğrenmesi kullandım. 

Kilometre satış fiyatı ve kümeleme arasındaki ilişkiyi görselleştirerek verideki yapıları daha iyi anladım.

Farklı modellerin performansını karşılaştırdım ve Random Forest modelinin en iyi sonuçları verdiğini gözlemledim. Hiperparametre optimizasyonu ile bu modelin performansını daha da iyileştirmeye çalıştım. Daha geniş bir zaman olsaydı büyük hiperparametre aralıklarını deneyerek daha da iyi sonuçlar elde edebilir miydim diye merak ediyorum.

Bu proje araç fiyatlandırması konusunda daha iyi kararlar almak için veri analizi ve makine öğrenmesinin gücünü göstermektedir.


# Kaynak 

https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
