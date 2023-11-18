# Ülkelere Göre Birliktelik Kuralları Analizi

Bu Python projesi, ülkelere göre birliktelik kuralları çıkarmak için kullanılan özel bir kütüphaneyi içermektedir. Proje, çeşitli veri manipülasyonları, tanımlayıcı veri analizi, görselleştirme, veri ön-işleme ve birliktelik analizi adımlarını içermektedir.

## Kütüphaneler

Proje, aşağıdaki kütüphaneleri kullanmaktadır:
- Veri manipulasyonları için: `numpy`, `pandas`
- Veri görselleştirme için: `Seaborn`, `Matplotlib`, `Plotly`
- Veri ön-işleme ve model oluşturma için: `sklearn`, `pickle`
- Birliktelik kuralları için: `mlxtend`

## Proje Aşamaları

### 1. Veri Setinin Tanımlayıcı Veri Analizi

Proje, veri setinin temel özelliklerini inceleyerek aşağıdaki bilgileri sağlar:
- Kayıt sayıları
- Nitelik sayıları
- Nitelik tipleri
- Merkezi eğilim ölçüleri
- Merkezden dağılım ölçüleri
- 5 sayı özeti

### 2. Verinin Görselleştirilmesi

Proje, veri setinin detaylı bir analizini sunmak için çeşitli görselleştirmeler kullanır. Bu görselleştirmeler arasında histogramlar, scatter plot'lar ve çeşitli grafikler bulunabilir.

### 3. Veri Seti Üzerinde Veri Ön-İşleme Çalışması

Proje, veri setinde yapılan ön-işleme çalışmalarını içerir. Bu çalışmalar arasında eksik veri tamamlama, aykırı değer giderme, ayrıklaştırma, ikilileştirme ve düzleştirme gibi işlemler yer alabilir.

### 4. Veri Setinin Birliktelik Kuralları Analizi

Proje, veri setinde bulunan verileri ülkelere göre gruplayarak birliktelik analizi yapılacak olan algoritmaya (örneğin Apriori Alg.) uygun hale getirir. Minimum destek değeri 0.01 ve minimum güven değeri 0.95 alınarak birliktelik kuralları oluşturulur ve yorumlanır.

## Kullanım

Projeyi kullanabilmek için sisteminizde Jupyter Notebook olması gerekmektedir. Ardından .ipynb dosyasını açıp `Run` butonuna tıklamanız yeterlidir. 
