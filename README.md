# Fashion-MNIST Görüntü Sınıflandırma ve Model Analizi

Bu depo, TensorFlow ve Keras kütüphaneleri kullanılarak geliştirilmiş uçtan uca bir yapay sinir ağı (YSA) görüntü sınıflandırma projesini içermektedir. Modelin görsel sınıflandırma kabiliyeti `Fashion-MNIST` veri seti üzerinde test edilmiştir.

## 📌 Proje Özeti ve Kazanımlar
* **Model Mimarisi:** Görüntü düzleştirme (Flatten), ReLU aktivasyonlu gizli katman (Dense) ve 10 farklı sınıf için Softmax çıkış katmanı ile tasarlanmış tam bağımlı sinir ağı.
* **Hiperparametre Analizi:** Model 10, 20 ve 30 epoch (eğitim turu) değerleriyle ayrı ayrı eğitilmiş, iterasyon sayısının doğruluk oranlarına ve öğrenme karakteristiğine etkisi analiz edilmiştir.
* **Performans Görselleştirme:** Eğitim süreci sonunda Validation Accuracy (Doğruluk) ve Validation Loss (Kayıp) grafikleri Matplotlib ile çizdirilmiş, modelin doygunluk noktaları gözlemlenmiştir.
* **Tahmin ve Doğrulama:** Test verisi üzerinden seçilen rastgele görüntülerin model tahminleri gerçek etiketleriyle görsel olarak karşılaştırılmıştır.

## 🛠 Kullanılan Teknolojiler
* **Python**
* **TensorFlow & Keras** (Model inşaası, derleme ve optimizasyon)
* **Matplotlib** (Eğitim metrikleri ve sonuç görselleştirme)
* **NumPy** (Matris operasyonları ve etiket manipülasyonu)
