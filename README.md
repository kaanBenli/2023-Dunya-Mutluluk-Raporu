Bu proje, 2023 Dünya Mutluluk Raporu verilerini kullanarak ülkelerin mutluluk skorlarını etkileyen faktörleri analiz eder. Proje kapsamında verilerin görselleştirilmesi, Temel Bileşenler Analizi (PCA) ile boyut indirgeme ve K-Means algoritması ile ülkelerin kümelenmesi işlemleri gerçekleştirilmiştir.

Öne Çıkan Özellikler: Kaggle üzerinden otomatik veri çekme ve sütun normalizasyonu.
Korelasyon Analizi: GSYİH, Sosyal Destek ve Sağlıklı Yaşam gibi faktörlerin mutluluk üzerindeki etkisinin regresyon analizi ile gösterimi.
PCA (Principal Component Analysis): 6 farklı göstergenin (özelliğin) varyans analizi ve 2 boyuta indirgenerek "Kalkınma" ve "Özgürlük" eksenlerine dönüştürülmesi.
K-Means Kümeleme: Ülkelerin benzer karakteristiklerine göre 4 ana gruba (Mutlu/Gelişmiş, Orta, Mutsuz vb.) ayrılması.
Spider Grafik: Türkiye ve Finlandiya gibi ülkelerin dünya ortalamasına göre kıyaslanmalı profil analizi. 

Kullanılan Teknolojiler
Python 3.x
Pandas & NumPy: Veri manipülasyonu
Matplotlib & Seaborn: İleri seviye veri görselleştirme.
Scikit-Learn: Standartlaştırma, PCA ve K-Means modelleme.
KaggleHub: Güncel veri setine erişim.

Analiz Çıktıları:
Faktör Analizi: Her bir değişkenin Mutluluk Skoru ile olan korelasyonu.
Scree Plot: PCA bileşenlerinin açıklanan varyans oranları.
PCA Biplot: Ülkelerin 2D düzlemdeki konumu ve özellik vektörleri.
Cluster Map: K-Means ile gruplandırılmış dünya haritası benzeri dağılım.
Radar Chart: Ülke bazlı performans profilleri.
