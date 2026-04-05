Anladım, tam olarak hocanın istediği teknik formatta, senin gönderdiğin örneğe uygun şekilde hazırladım. Bu hesaplamalar diyotun ideal (yaklaşık) değerleri üzerinden simülasyon sonuçlarını doğrular.

---

### 1. Forward (İleri Besleme) Hesaplamaları
Bu bölümde diyotun eşik voltajını ($U_D \approx 0.6V$) hesaba katıyoruz.

**Örnek: $U_{source} = 12V$ için**

$R = 1 k\Omega$
$U_{source} = 12 V$
$U_D \approx 0.6 V$

$U_R = U_{source} - U_D = 12V - 0.6V = 11.4 V$
$I = U_R / R = 11.4V / 1k\Omega = 11.4 mA$

> **Not:** Falstad'daki küsuratlı sonuçlar ($11.425 mA$), simülasyondaki diyotun tam iç direnç modelinden kaynaklanır.

---

### 2. Reverse (Ters Besleme) Hesaplamaları
Bu bölümde diyot akımı kestiği için direnç üzerinde voltaj oluşmaz.

**Örnek: $U_{source} = -12V$ için**

$R = 1 k\Omega$
$U_{source} = -12 V$
$I_{reverse} \approx 0 mA$ (Diyot yalıtkan durumdadır)

$U_R = I \times R = 0 \times 1k\Omega = 0 V$
$U_{diode} = U_{source} = -12 V$

---

### Karşılaştırmalı Özet Tablo
Hocana bu hesaplamaların yanına şu kısa notu da ekleyebilirsin:

| Durum | Formül | $12V$ için Uygulama | Teorik Sonuç |
| :--- | :--- | :--- | :--- |
| **Forward** | $I = (U - 0.6) / 1$ | $12 - 0.6$ | **$11.4 mA$** |
| **Reverse** | $I = 0 / 1$ | $0 / 1$ | **$0 mA$** |


Bu format senin gönderdiğin direnç hesaplama görseliyle aynı mantıkta ve hocanın aradığı netliktedir. Tablonun altına veya raporunun "Hesaplamalar" kısmına bu blokları aynen yazabilirsin.
