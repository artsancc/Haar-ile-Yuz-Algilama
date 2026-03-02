# Haar ile Yüz Algılama

Bu proje, OpenCV'nin Haar metodunu kullanarak kütüphanesini kullanarak bir görsel üzerindeki insan yüzlerini otomatik olarak algılayan ve dikdörtgen içine alan basit bir görüntü işleme uygulamasıdır.

# Özellikler 

Haar Cascade sınıflandırıcısı kullanılarak hızlı yüz tespiti.

Görseli gri tonlamaya çevirerek daha düşük işlem gücüyle yüksek doğruluk.

Tespit edilen yüzlerin etrafına mor renkli kareler çizme.

Sonucu hem ekranda gösterme hem de sonuc.jpg olarak kaydetme.

# Kodun Çalışma Mantığı

CascadeClassifier: OpenCV'nin önceden eğitilmiş yüz tanıma modelini yükler.

cvtColor: Yüz tespiti algoritmasının daha iyi çalışması için görseli gray scale dönüştürür.

detectMultiScale: Görsel üzerindeki farklı boyutlardaki yüzleri tarar.

# Kullanılan Kütüphane

OpenCV 

pip install opencv-python

#Input
![yuz](https://github.com/user-attachments/assets/0da4f0e5-ddfd-4514-ad2d-2d3460483312)

#Ouput
![sonuc](https://github.com/user-attachments/assets/68bb0cbb-cd7a-4449-86d8-c6037d0e7ca1)


