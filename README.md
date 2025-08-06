# 📌 BYM308 - Yapay Zekaya Giriş Final Projesi

Bu proje, **BYM308 - Yapay Zekaya Giriş** dersi kapsamında hazırlanmış bir final çalışmasıdır. Projede, nesne tespiti (object detection) için popüler bir derin öğrenme algoritması olan **YOLOv5 (You Only Look Once v5)** kullanılmıştır.

Amaç, belirli bir veri kümesi üzerinde YOLOv5 modeli eğiterek, nesneleri doğru bir şekilde tespit edebilen bir yapay zeka uygulaması geliştirmektir.

---

## 🧠 Kullanılan Yöntem ve Teknolojiler

- YOLOv5 (PyTorch tabanlı)
- Google Colab (Jupyter Notebook)
- Python 3
- CUDA destekli eğitim (Google Colab GPU)
- OpenCV & Matplotlib
- Labeling ve model değerlendirme yöntemleri

---

## 🗂️ Proje Dosyaları

| Dosya Adı                 | Açıklama                                      |
|--------------------------|-----------------------------------------------|
| `FinalProjeYolo5.ipynb`  | Model eğitimi, doğrulama ve test süreçlerini içerir |
| `best.pt`                | Eğitilmiş YOLOv5 model ağırlık dosyası        |
| `Final Sunum.pptx`       | Projeyi anlatan sunum dosyası                 |
| `VeriSeti/`              | Etiketlenmiş eğitim ve test görselleri       |

---

## ⚙️ Kurulum ve Çalıştırma

Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. YOLOv5 deposunu klonlayın:
    ```bash
    git clone https://github.com/ultralytics/yolov5
    cd yolov5
    pip install -r requirements.txt
    ```

2. `FinalProjeYolo5.ipynb` dosyasını Google Colab üzerinde açın.

3. Modeli eğitmek ve test etmek için hücreleri sırayla çalıştırın.

4. `best.pt` modelini kullanarak kendi görüntüleriniz üzerinde nesne tespiti gerçekleştirebilirsiniz.

---
