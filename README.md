# Merge-sort-proje
Kodluyoruz Eğitimi kapsamında açtığım bir proje
Merge Sort algoritmasını adım adım uygulayalım:

Başlangıç:

[16, 21, 11, 8, 12, 22]
Diziyi ortadan ikiye bölme:

[16, 21, 11] ve [8, 12, 22]
Her iki yarıyı tekrar bölme:

[16, 21] ve [11]
[8, 12] ve [22]
Daha fazla bölme:

[16] ve [21]
[8] ve [12]
Alt dizileri sıralama ve birleştirme:

[16] ve [21] birleştirilir ve sıralanır: [16, 21]
[8] ve [12] birleştirilir ve sıralanır: [8, 12]
Kısmi sıralı dizileri birleştirme:

[16, 21] ve [11] birleştirilir ve sıralanır: [11, 16, 21]
[8, 12] ve [22] birleştirilir ve sıralanır: [8, 12, 22]
Son olarak iki yarıyı birleştirme ve sıralama:

[11, 16, 21] ve [8, 12, 22] birleştirilir ve sıralanır: [8, 11, 12, 16, 21, 22]
Aşamaların Detaylı Gösterimi
Başlangıç:

[16, 21, 11, 8, 12, 22]
İkiye Bölme:

Sol: [16, 21, 11]
Sağ: [8, 12, 22]
Sol Kısmı Bölme:

Sol: [16, 21]
Sağ: [11]
Sağ Kısmı Bölme:

Sol: [8, 12]
Sağ: [22]
Alt Dizileri Sıralama ve Birleştirme:

[16, 21] -> [16], [21] -> [16, 21]
[11] zaten sıralı.
[8, 12] -> [8], [12] -> [8, 12]
[22] zaten sıralı.
Kısmi Sıralı Dizileri Birleştirme:

[16, 21] ve [11] -> [11, 16, 21]
[8, 12] ve [22] -> [8, 12, 22]
Son Birleştirme ve Sıralama:

[11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]
Big-O Gösterimi
Merge Sort algoritmasının en kötü durum (worst case), en iyi durum (best case) ve ortalama durum (average case) zaman karmaşıklığı: O(n log n)

Bu algoritma her zaman O(n log n) karmaşıklığına sahiptir çünkü dizi her zaman log n derinliğinde bölünür ve her seviyede n öğe birleştirilir.
