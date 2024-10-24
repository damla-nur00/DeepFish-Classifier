Akbank Derin Öğrenme Boostcamp Projesi
Balık Türleri Sınıflandırma Projesi

Projenin Amacı
Bu projede, farklı balık türlerini tanımak ve sınıflandırmak için bir sinir ağı modeli geliştirilmiştir. Görüntü işleme teknikleri ve derin öğrenme algoritmaları kullanılarak, balık türleri yüksek doğrulukla sınıflandırılır.

Projenin Yapısı
1. Veri Hazırlığı
Balık türlerine ait görüntüler, OpenCV ile işlenip yeniden boyutlandırılır ve modelin eğitimi için kategorik etiketlerle etiketlenir. Görseller, eğitim ve test setlerine ayrılarak modelin öğrenme süreci için hazırlanır.

2. Model Kurulumu
Derin öğrenme modeli, TensorFlow ve Keras kullanılarak oluşturulur. Convolutional Neural Network (CNN) mimarisi ile görüntüdeki balık türleri tespit edilir. Modelin katmanları, görüntüdeki özellikleri öğrenmek ve sınıflandırmak için optimize edilmiştir.

3. Eğitim ve Değerlendirme
Model, eğitim verileri üzerinde eğitilir. Adam optimizer ve cross-entropy kaybı ile model optimize edilir. Eğitim sırasında doğruluk ve kayıp değerleri izlenir, doğrulama seti ile modelin performansı değerlendirilir.

4. Sonuç Analizi
Modelin doğruluğu ve başarısı, confusion matrix ve diğer metriklerle analiz edilir. Performans grafikleri görselleştirilir ve modelin doğruluk oranı ile diğer metrikler gözden geçirilir.

5. Test Edilmesi
Model, daha önce görmediği test verisi üzerinde denetlenir. Sonuçlar, modelin gerçek dünya performansını değerlendirmek için kullanılır.

Kullanılan Teknolojiler
Python 3.x: Proje dili
TensorFlow & Keras: Derin öğrenme modellerini eğitmek ve değerlendirmek için.
OpenCV: Görüntü işleme ve veri ön işleme adımlarında kullanıldı.
Pandas: Veri işleme ve düzenleme.
NumPy: Sayısal hesaplama ve matris işlemleri.
Matplotlib & Seaborn: Sonuçların görselleştirilmesi.

Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Detaylar için LICENSE dosyasına göz atabilirsiniz.

Kaggle Link
https://www.kaggle.com/code/damlahande/akbank-derinogrenme
