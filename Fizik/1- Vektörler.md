# Vektörler

## Vektörün Tanımı

* **Vektör**: Doğrultusu, yönü ve büyüklüğü olan niceliktir.
* Eğer bir nicelik yalnızca sayı ile ifade ediliyorsa, buna **skaler** denir.

Örnek:

* $\vec{a}$ → vektör (doğrultu, yön, büyüklük içerir).
* $a$ → skaler (yalnızca sayı değeri).

## Vektörlerin Özellikleri

1. **Doğrultu**: Vektörün üzerinde bulunduğu çizgi.
2. **Yön**: Vektörün okunun gösterdiği taraf.
3. **Büyüklük (şiddet)**: Vektörün uzunluğu ya da sayısal değeri.

$\displaystyle \vec{d} = \vec{b} \implies$ Büyüklük, doğrultu ve yön aynı  
$\displaystyle \vec{a} = -\vec{b} \implies$ Doğrultu ve büyüklük aynı, yön zıt


---

## Vektörlerde Toplama Yöntemleri

### 1. Uç Uca Ekleme Yöntemi

* Birinci vektörün ucuna ikinci vektörün başlangıcı eklenir.
* Başlangıç noktası ile son nokta arasına çizilen vektör toplamı verir.

```
A ─────► B ─────► C  
AC vektörü = AB + BC
```

---

### 2. Paralelkenar Yöntemi

* İki vektör ortak bir noktadan çizilir.
* Bu iki vektör paralelkenar oluşturacak şekilde tamamlanır.
* Paralelkenarın köşegen çizgisi toplam vektördür.

---

### 3. Bileşenlerine Ayırma Yöntemi

* Vektör, x ve y eksenine paralel olacak şekilde bileşenlerine ayrılır.
* Trigonometrik ilişkiler kullanılır:

$$
F_x = F \cdot \cos\theta, \quad F_y = F \cdot \sin\theta
$$

---

### 4. Sinüs – Kosinüs Kullanımı

* Özellikle kuvvet vektörlerini eksenlere ayırmada kullanılır.

---

## Örnek Soru

**Soru:**
Bir cisim üzerine $F = 10 \, \text{N}$ büyüklüğünde bir kuvvet, $37^\circ$ açıyla uygulanıyor.
Bileşenlerini bulunuz.

**Çözüm:**

$$
F_x = 10 \cdot \cos 37^\circ = 10 \cdot 0.8 = 8 \, \text{N}
$$

$$
F_y = 10 \cdot \sin 37^\circ = 10 \cdot 0.6 = 6 \, \text{N}
$$

---

## Vektörlerde Toplamanın Özel Durumları

Eğer iki vektörün büyüklükleri eşit ($F$) ise:

| Açı (θ)     | Sonuç vektör büyüklüğü                             |
| ----------- | -------------------------------------------------- |
| $0^\circ$   | $2F$                                               |
| $180^\circ$ | $0$                                                |
| $90^\circ$  | $\sqrt{F^2 + F^2} = F\sqrt{2}$                     |
| $60^\circ$  | $\sqrt{F^2 + F^2 + 2F^2\cos 60^\circ} = \sqrt{3}F$ |
| $120^\circ$ | $\sqrt{F^2 + F^2 + 2F^2\cos 120^\circ} = F$        |

---

## Kosinüs Teoremi

İki vektör $\vec{a}, \vec{b}$ arasındaki açı $\theta$ ise toplam vektör büyüklüğü:

$$
|\vec{a} + \vec{b}| = \sqrt{a^2 + b^2 + 2ab \cos\theta}
$$

Bu formül sayesinde herhangi iki vektörün büyüklükleri ve aralarındaki açı bilindiğinde toplam bulunabilir.

