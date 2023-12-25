# Churn Prediction with Artificial Neural Networks (ANN)

Bu proje, yapay sinir ağları (ANN) kullanarak müşteri kayıplarını (churn) tahmin etmek için bir model geliştirmeyi amaçlamaktadır. 


## Veri Seti

Bu proje için kullanılan veri seti "Churn_Modelling.csv" adlı dosyada bulunmaktadır. Veri seti, müşteri ile ilgili çeşitli demografik ve bankacılık verilerini içermektedir.

Elimizde bir bankanın müşterilerinin detaylarının bulunduğu bir veri kümesi vardır ve hedef değişken, müşterinin bankadan ayrılıp ayrılmadığını (hesabını kapatıp kapatmadığını) veya müşteri olmaya devam edip etmediğini yansıtan ikili bir değişkendir.

Verilen veri kümesindeki özellikler şunlardır:

rownumber: 1'den 10000'e kadar Satır Numaraları.
customerid: Her müşteriyi tanımlayan benzersiz bir kimlik.
surname: Müşterinin soyadı.
creditscore: Kredi puanı: Kredi puanı, bir tüketicinin kredi itibarını gösteren 300-850 arasında bir sayıdır.
geography: Coğrafya: Müşterinin ait olduğu ülke.
Gender: Müşterinin cinsiyeti: Erkek, Kadın
Age: Müşterinin müşteri olduğu andaki yıl cinsinden mevcut yaşı.
tenure: Müşterinin bankada geçirdiği yıl sayısı.
balance: Müşterinin banka bakiyesi.
numofproducts: Müşterinin kullanmakta olduğu banka ürünü sayısı.
hascrcard: Müşteriye banka tarafından verilen kredi kartı sayısı.
isactivemember: Müşterinin şirketten çıktığı andan önce bankada aktif olup olmadığını gösteren ikili bayrak ("exited" değişkenine kaydedilir)
exited: Müşteri bankadaki hesabını kapatmışsa 1 ve müşteri elde tutulmuşsa 0 binary etiketi.


## Kullanılan Teknolojiler

- Python
- TensorFlow ve Keras kütüphaneleri
- Pandas, NumPy ve diğer veri işleme kütüphaneleri
- Scikit-learn (GridSearchCV için)

## Projeyi Çalıştırma

1. `Churn_Modelling.csv` dosyasını projenin ana dizinine ekleyin.
2. `churn_prediction_ANN.ipynb` adlı Jupyter Notebook dosyasını açın.
3. Notebook'taki adımları takip ederek modeli eğitin ve test edin.

## Modelin Değerlendirilmesi

- Modelin performansı, doğruluk (accuracy), hatırlama (recall), AUC (Area Under Curve) gibi metriklerle değerlendirilmiştir.
- Confusion matrix ve sınıflandırma raporu sonuçlarına da README dosyasından erişilebilir.

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
