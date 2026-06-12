# morphological_analysis
BLM5023 Doğal Dil İşleme Projesi YL

# Türkçe Morfolojik Etiketleme (POS Tagging) Projesi

Bu proje, Türkçe metinler üzerinde **Koşullu Rastgele Alanlar (Conditional Random Fields - CRF)** algoritmasını kullanarak Sözcük Türü Etiketleme (Part-of-Speech Tagging) işlemini gerçekleştirmektedir. Çalışma, metin içerisindeki kelimelerin morfolojik yapılarını analiz ederek dilbilgisel kategorilerini (isim, fiil, sıfat vb.) otomatik olarak tespit etmeyi amaçlar.

## Proje Klasör Yapısı
- `main.py`: Eğitim, tahmin, metrik hesaplama ve grafik oluşturma süreçlerini içeren ana kod dosyası.
- `dataset.conll`: Etiket standardizasyonu yapılmış eğitim ve test verisi.
- `requirements.txt`: Projenin çalışması için gerekli kütüphanelerin listesi.
- `confusion_matrix.png`: Modelin hata analizi için üretilen karışıklık matrisi görseli.
- `performance_metrics.png`: Sınıf bazlı başarı oranlarını gösteren performans grafiği.

## Kurulum ve Çalıştırma

### 1. Gereksinimler
Projeyi çalıştırmadan önce sisteminizde Python 3.x yüklü olmalıdır. Gerekli kütüphaneleri yüklemek için terminalde şu komutu çalıştırın:

```bash
pip install -r requirements.txt
