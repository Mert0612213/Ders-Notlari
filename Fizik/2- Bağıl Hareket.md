# Bağıl ve Bileşik Hareket

## 1. Bağıl Hareket (Relatif Hareket)

### Tanım
Bir cismin hareketinin başka bir cisme göre incelenmesidir.  
Hareketin gözlemlendiği referans çerçevesine göre hız ve yön değişebilir.

### Temel Formül (1 Boyut)

v_AC = v_AB + v_BC

- v_AC → C cismine göre A cisminin hızı  
- v_AB → B cismine göre A cisminin hızı  
- v_BC → C cismine göre B cisminin hızı  

---

### Örnek 1: Tren ve Yolcu

- Tren 5 m/s hızla hareket ediyor.  
- Yolcunun tren içindeki hızı 2 m/s.

**Yerdeki hız (aynı yönde):**  
v_yolcu/yer = v_yolcu/tren + v_tren/yer = 2 + 5 = 7 m/s

**Yerdeki hız (ters yönde):**  
v_yolcu/yer = -2 + 5 = 3 m/s

---

### Örnek 2: İki Araç

- Araç A, yolda 60 km/h hızla gidiyor.  
- Araç B, A’ya göre 20 km/h hızla ilerliyor (aynı yönde).  

**B’ye göre A’nın hızı:**  
v_A/B = v_A/yer - v_B/yer = 60 - 20 = 40 km/h

---

## 2. Bileşik Hareket (Klasik Nehir/Yüzücü Problemleri)

### Tanım
Bir cismin hareketinin **iki farklı bileşene** ayrıldığı durumdur:  
1. Akış doğrultusuna paralel (x ekseni)  
2. Akışa dik (y ekseni)  

### Temel Formüller

- Düz x yönünde hareket: x = v · t  
- İki bileşenli hareket: v_toplam = √(v_x² + v_y²)  

---

### Örnek 1: Nehir ve Yüzücü

- Nehir hızı: v_r = 2 m/s  
- Yüzücünün suya göre hızı: v_s = 3 m/s (nehire dik)  
- Nehrin genişliği: L = 100 m

**Süre:**  
t = L / v_s = 100 / 3 ≈ 33.33 saniye

**Yolcunun kıyıya göre kayması (nehir yönünde):**  
x = v_r · t = 2 · 33.33 ≈ 66.66 m

> Not: Dere sola ya da sağa aksa bile yüzücünün **nehire dik hareket süresi değişmez**, yalnızca x yönündeki yer değiştirmesi değişir.

---

### Örnek 2: Nehir Boyunca Hedefe Gitmek

- Yüzücü karşı kıyıya tam dik gitmek istiyor.  
- Gereken açı: θ = arcsin(v_r / v_s)  

- Toplam hız (karşı kıyıya göre): v_toplam = √(v_s² - v_r²)  

- Süre: t = L / v_toplam  

---

### Örnek 3: Yatay + Dikey Bileşen

- Nehir boyunca hareket: x = v_r · t  
- Nehre dik: y = v_s · t  
- Toplam yer değiştirme: s = √(x² + y²)

---

## Özet Kurallar

1. **Bağıl hareket:** Hızlar referans çerçevesine göre toplanır.  
2. **Bileşik hareket:** Hareket dik bileşenlere ayrılır; süre x eksenine göre hesaplanır.  
3. Nehir problemlerinde:  
   - Dik hareket süresi = Nehre dik mesafe / yüzücünün suya göre hızı  
   - Nehre paralel kayma = Nehir hızı × süre  
   - Hedefe doğru gitmek için açı = arcsin(v_r / v_s)
