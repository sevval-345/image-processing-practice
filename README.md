# image-processing-basics

Bu proje, görüntü işleme süreçlerini ham veriden anlamlı bilgiye dönüştüren bir çalışma setidir. `image_processing_basics` dosyası içerisinde temel manipülasyonlardan, ileri düzey görüntü filtreleme ve makine öğrenmesi tabanlı sınıflandırma tekniklerine kadar kapsamlı bir uygulama hattı bulunmaktadır.

## 🚀 Proje Kapsamı
Bu çalışma, bir görüntü üzerinde yapılabilecek temel ve orta seviye işlemleri tek bir pipeline içerisinde toplamaktadır.

### Uygulanan İşlemler
* **Görselleştirme ve Kanal Analizi:** Görüntülerin (RGB) kanallarına ayrılması, piksel değerlerinin incelenmesi ve çoklu grafik gösterimi.
* **Geometrik Dönüşümler:** Kırpma (cropping), yeniden boyutlandırma (resize), döndürme (rotation) ve aynalama (flip) işlemleri.
* **Renk Uzayı Dönüşümleri:** Grayscale, HSV ve LAB uzaylarına geçiş; HSV ile hedef odaklı renk maskeleme.
* **Histogram Analizi:** Piksel yoğunluk dağılımlarının incelenmesi ve histogram eşitleme (equalization) ile kontrast artırma.
* **Filtreleme ve Gürültü Giderme:** Ortalama, Gaussian, Medyan ve Bilateral filtrelerin karşılaştırmalı analizi (PSNR metriği ile).
* **Kenar Tespiti:** Sobel, Laplacian ve Canny kenar dedektörleri ile nesne sınırı belirleme.
* **Morfolojik İşlemler:** Aşındırma (erosion), genişletme (dilation), açma ve kapama operatörleri.
* **Makine Öğrenmesi Entegrasyonu:** Kontur analizi ile nesne tespiti ve KNN (K-Nearest Neighbors) algoritması ile el yazısı rakam sınıflandırma.

## 🛠 Kullanılan Teknolojiler
* **Görüntü İşleme:** `OpenCV (cv2)`, `Pillow (PIL)`, `SciPy`
* **Matematik ve Veri:** `NumPy`
* **Görselleştirme:** `Matplotlib`
* **Makine Öğrenmesi:** `Scikit-learn`

---
*Bu proje, görüntü işleme pipeline'larını (girişten sonuca) anlamak isteyenler için bir başvuru kaynağıdır.*
