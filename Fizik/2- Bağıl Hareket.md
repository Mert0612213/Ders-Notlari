# Bağıl ve Bileşik Hareket

## 1. Bağıl Hareket (Relatif Hareket)

### Tanım
Bir cismin hareketinin başka bir cisme göre incelenmesidir.  
Hareketin gözlemlendiği referans çerçevesine göre hız ve yön değişebilir.

### Temel Formül (1 Boyut)

$$
v_{AC} = v_{AB} + v_{BC}
$$

- $v_{AC}$ → C cismine göre A cisminin hızı  
- $v_{AB}$ → B cismine göre A cisminin hızı  
- $v_{BC}$ → C cismine göre B cisminin hızı  

---

### Örnek 1: Tren ve Yolcu

- Tren 5 m/s hızla hareket ediyor.  
- Yolcunun tren içindeki hızı 2 m/s.

**Yerdeki hız:**  
$$
v_{\text{yolcu/yer}} = v_{\text{yolcu/tren}} + v_{\text{tren/yer}} = 2 + 5 = 7 \, \text{m/s}
$$`

- Eğer yolcu trenin ters yönünde yürürse:  
$$
v_{\text{yolcu/yer}} = -2 + 5 = 3 \, \text{m/s}
$$

---

### Örnek 2: İki Araç

- Araç A, yolda 60 km/h hızla gidiyor.  
- Araç B, A’ya göre 20 km/h hızla ilerliyor (aynı yönde).  

**B’ye göre A’nın hızı:**  
$$
v_{A/B} = v_{A/yer} - v_{B/yer} = 60 - 20 = 40 \, \text{km/h}
$$

---

## 2. Bileşik Hareket (Klasik Nehir/Yüzücü Problemleri)

### Tanım
Bir cismin hareketinin **iki farklı bileşene** ayrıldığı durumdur:  
1. Akış doğrultusuna paralel (x ekseni)  
2. Akışa dik (y ekseni)  

### Temel Formüller

- Düz x yönünde hareket:  
$$
x = v \cdot t
$$

- İki bileşenli hareket:  
$$
v_{\text{toplam}} = \sqrt{v_x^2 + v_y^2}  
$$

---

### Örnek 1: Nehir ve Yüzücü

- Nehir hızı: $v_r = 2 \, \text{m/s}$  
- Yüzücünün suya göre hızı: $v_s = 3 \, \text{m/s}$ (nehire dik)  
- Nehrin genişliği: $L = 100 \, \text{m}$

**Süre:**  
$$
t = \frac{L}{v_s} = \frac{100}{3} \approx 33.33 \, \text{saniye}
$$

**Yolcunun kıyıya göre kayması (nehir yönünde):**  
$$
x = v_r \cdot t = 2 \cdot 33.33 \approx 66.66 \, \text{m}
$$

> Not: Dere sola ya da sağa aksa bile yüzücünün **nehire dik hareket süresi değişmez**, yalnızca x yönündeki yer değiştirmesi değişir.

---

### Örnek 2: Nehir Boyunca Hedefe Gitmek

- Yüzücü karşı kıyıya tam dik gitmek istiyor.  
- Gereken açı:  
$$
\theta = \arcsin\left(\frac{v_r}{v_s}\right)
$$

- Toplam hız (karşı kıyıya göre):  
$$
v_{\text{toplam}} = \sqrt{v_s^2 - v_r^2}  
$$

- Süre:  
$$
t = \frac{L}{v_{\text{toplam}}}  
$$

---

### Örnek 3: Yatay + Dikey Bileşen

- Nehir boyunca hareket: $x = v_r \cdot t$  
- Nehre dik: $y = v_s \cdot t$  
- Toplam yer değiştirme:  
$$
s = \sqrt{x^2 + y^2}
$$

---

## Özet Kurallar

1. **Bağıl hareket:** Hızlar **referans çerçevesine göre toplanır**.  
2. **Bileşik hareket:** Hareket **dik bileşenlere ayrılır**, süre x eksenine göre hesaplanır.  
3. Nehir problemlerinde:  
   - Dik hareket süresi = Nehre dik mesafe / yüzücünün suya göre hızı  
   - Nehre paralel kayma = Nehir hızı × süre  
   - Hedefe doğru gitmek için açı = $\arcsin(v_r/v_s)$  

---

