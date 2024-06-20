# fashion-mnist-classification
Fashion MNIST veri seti ile görüntü sınıflandırma projesi

# Fashion MNIST Classification

Bu proje, Keras kütüphanesindeki Fashion MNIST veri setini kullanarak görüntü sınıflandırma işlemi gerçekleştirmektedir.

## Proje Amacı
Bu projenin amacı, çeşitli makine öğrenmesi algoritmalarını kullanarak moda ürünlerinin sınıflandırılmasını sağlamaktır.

## Kullanılan Veri Seti
- **Fashion MNIST:** Keras kütüphanesinden alınan bu veri seti, 10 farklı sınıfa ait 28x28 piksel boyutunda gri tonlamalı 70.000 moda ürününün görüntüsünden oluşur.

## Proje Adımları
1. Veri Seti Seçimi ve Yüklenmesi
2. Veri Ön İşleme
3. Model Oluşturup Eğitme
4. Sonuçları Değerlendirme

## Temel Bulgular
- KNN algoritması kullanılarak yapılan sınıflandırma sonucunda %85.25 doğruluk elde edilmiştir.

## Kullanım
Aşağıdaki kodu çalıştırarak veri setini yükleyebilirsiniz:

```python
from keras.datasets import fashion_mnist

(X_train, y_train), (X_test, y_test) = fashion_mnist.load_data()
