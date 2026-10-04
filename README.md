# fizik-lab-analizleri
# Fizik I Laboratuvarı - Veri Analizi ve İstatistik

Bu depoda, Mekanik Laboratuvarı kapsamında gerçekleştirdiğimiz deneylerin ham verileri, hata analizleri ve Python (Matplotlib/NumPy) görselleştirmeleri yer almaktadır.

## Deney 01: Uzunluk Ölçümleri (Kumpas ve İstatistiksel Analiz)
- **Ekip:** Masa Grubu Ortak Ölçümü (Grup 4)
- **Analiz:** Utku Deniz Cansaran

### Gözlem ve Hata Analizi:
Ölçüm serisinde 3. veri noktası (2.30 cm), ±σ standart sapma sınırının belirgin biçimde dışına çıkmıştır. Bu durum verniyer skalasının okunmasındaki olası sistematik bir operatör hatasına işaret etmektedir. Veri şeffaflığı adına bu değer silinmemiş, aykırı değer (outlier) olarak grafikte belgelenmiştir.
- **Mikrometre Ölçümleri:** 20 adet kalınlık ölçümünün `np.unique` ve sütun grafiği (`plt.bar`) ile frekans dağılımı analizi.
