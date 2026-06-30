Görüntü İşleme ve Analiz Uygulamaları
Bu proje, görüntü işleme dünyasına giriş yapmak, temel manipülasyon tekniklerini öğrenmek ve görüntü verilerini makine öğrenmesi modelleriyle sınıflandırmak için geliştirilmiş kapsamlı bir çalışma setidir.  
PY
📋 Proje İçeriği ve Yapılan İşlemler
Proje kapsamında gerçekleştirilen temel işlemler şunlardır:
1. Veri Hazırlama ve Görselleştirme
Veri Setleri: scipy (gerçek fotoğraflar) ve sklearn (el yazısı rakamlar) veri setlerinin yüklenmesi.  
PY
Kanal Ayrıştırma: Renkli görüntülerin (RGB) kırmızı, yeşil ve mavi kanallarına ayrıştırılarak bağımsız incelenmesi.  
PY
Piksel Analizi: Belirli koordinatlardaki piksel değerlerinin okunması ve görselleştirilmesi.  
PY
2. Temel Görüntü Manipülasyonu
Kırpma (Cropping): NumPy dilimleme yöntemleri kullanılarak görüntünün belirli bir bölgesinin kesilmesi.  
PY
Yeniden Boyutlandırma: Görüntülerin çözünürlüklerinin değiştirilmesi.  
PY
Döndürme ve Çevirme: Görüntülerin derece bazlı döndürülmesi (45°), yatay ve dikey aynalama işlemlerinin yapılması.  
PY
3. Renk Uzayı Dönüşümleri
Grayscale: Görüntülerin gri tonlamaya çevrilmesi.  
PY
HSV ve LAB: Görüntünün renk maskeleme gibi özel işlemler için HSV ve LAB uzaylarına taşınması.  
PY
Renk Maskeleme: HSV uzayı kullanılarak görüntüden sadece belirli renklerin (örneğin yeşil) ayrıştırılması.  
PY
4. Histogram ve İyileştirme
Histogram Analizi: Gri tonlamalı ve RGB görüntüler için piksel dağılımlarının incelenmesi.  
PY
Histogram Eşitleme: Düşük kontrastlı görüntülerde (özellikle karanlık bölgelerde) kontrastın iyileştirilmesi.  
PY
5. Filtreleme ve Gürültü Giderme
Gürültü Ekleme: Görüntülere yapay gürültü ekleyerek gerçek hayat koşullarının simüle edilmesi.  
PY
Filtreler: Ortalama (Box), Gaussian, Medyan ve Bilateral filtreler ile gürültü temizleme karşılaştırmaları.  
PY
PSNR Analizi: Uygulanan filtrelerin başarısının Peak Signal-to-Noise Ratio (PSNR) değeri ile dB cinsinden ölçülmesi.  
PY
6. Kenar Tespiti ve Morfoloji
Kenar Dedektörleri: Sobel, Laplacian ve Canny algoritmaları ile nesne sınırlarının belirlenmesi.  
PY
Morfolojik İşlemler: Aşındırma (Erosion), Genişletme (Dilation), Açma (Opening) ve Kapama (Closing) yöntemleriyle görüntü üzerindeki yapısal düzenlemeler.  
PY
7. Makine Öğrenmesi (Sınıflandırma)
Kontur Analizi: Nesnelerin konturlarının bulunması, alan ve çevre uzunluklarının hesaplanması, nesne etrafına dikdörtgen çizilmesi.  
PY
KNN Sınıflandırma: El yazısı rakam veri setinin KNeighborsClassifier kullanılarak eğitilmesi, tahmin edilmesi ve başarısının (Confusion Matrix ile) değerlendirilmesi.  
PY
🛠 Kullanılan Kütüphaneler
NumPy & SciPy: Sayısal işlemler ve veri seti yönetimi.  
PY
OpenCV (cv2): Görüntü işleme ve bilgisayarlı görü algoritmaları.  
PY
Matplotlib: Grafik ve görselleştirme işlemleri.  
PY
Scikit-learn: Makine öğrenmesi modelleri ve veri normalizasyonu.  
PY
Bu proje, görüntü verilerinin ham halinden anlamlı bilgilere dönüştürülmesine kadar uzanan bir "pipeline" (işlem hattı) yapısını temsil etmektedir.
