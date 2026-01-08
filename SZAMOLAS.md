# Radioaktivitás – számolási magyarázó

## 1. Atommag jelölése

Egy atommagot így írunk fel:

⁽ᴬ⁾₍Z₎X

ahol:
- **A** – tömegszám (proton + neutron)
- **Z** – rendszám (protonok száma)
- **X** – az elem vegyjele

A bomlások során **A és Z változásából** határozzuk meg,
**milyen elem keletkezik**.

---

## 2. Alfa-bomlás (α)

### Mi történik?
Az atommag egy **hélium-magot (⁴₂He)** bocsát ki.

### Változások
- Tömegszám: **A − 4**
- Rendszám: **Z − 2**

### Általános alak
⁽ᴬ⁾₍Z₎X → ⁽ᴬ⁻⁴⁾₍Z⁻²₎Y + ⁴₂He

### Számolási példa
Urán bomlása:

⁽²³⁸⁾₍₉₂₎U → ?

Számolás:
- A = 238 − 4 = **234**
- Z = 92 − 2 = **90**

A 90-es rendszámú elem: **tórium (Th)**

### Eredmény
⁽²³⁸⁾₍₉₂₎U → ⁽²³⁴⁾₍₉₀₎Th + ⁴₂He

---

## 3. Béta mínusz bomlás (β⁻)

### Mi történik?
Egy **neutron protonná alakul**, és egy elektron lép ki a magból.

### Változások
- Tömegszám: **nem változik**
- Rendszám: **Z + 1**

### Általános alak
⁽ᴬ⁾₍Z₎X → ⁽ᴬ⁾₍Z⁺¹₎Y + e⁻

### Számolási példa
Szén-14 bomlása:

⁽¹⁴⁾₍₆₎C → ?

Számolás:
- A = 14 (változatlan)
- Z = 6 + 1 = **7**

A 7-es rendszámú elem: **nitrogén (N)**

### Eredmény
⁽¹⁴⁾₍₆₎C → ⁽¹⁴⁾₍₇₎N + e⁻

---

## 4. Gamma-sugárzás (γ)

### Mi történik?
A mag **csak energiát veszít**, szerkezete nem változik.

### Változások
- Tömegszám: **nem változik**
- Rendszám: **nem változik**

### Alak
⁽ᴬ⁾₍Z₎X* → ⁽ᴬ⁾₍Z₎X + γ

⚠️ **Nem keletkezik új elem**, csak az energia csökken.

---

## 5. Több egymást követő bomlás

Ha egymás után több bomlás van, **minden lépést külön kell számolni**.

### Példa
Két alfa-bomlás egymás után:

Kezdet:
⁽²³⁸⁾₍₉₂₎U

1. alfa:
- A = 238 − 4 = 234
- Z = 92 − 2 = 90 → Th

2. alfa:
- A = 234 − 4 = 230
- Z = 90 − 2 = 88 → Ra

### Végső elem:
⁽²³⁰⁾₍₈₈₎Ra (rádium)

---

## 6. Gyors ellenőrző táblázat

| Bomlás típusa | A változás | Z változás |
|--------------|-----------|-----------|
| Alfa (α)     | −4        | −2        |
| Béta (β⁻)    | 0         | +1        |
| Gamma (γ)    | 0         | 0         |

---

## Vizsgatipp
👉 **Mindig A-val és Z-vel számolj először**,  
👉 utána **nézd meg a periódusos rendszerben**, melyik elemhez tartozik a Z érték.









# Radioaktivitás – Felezési idő (T₁/₂) – számolási magyarázó

## Mi a felezési idő?
A **felezési idő (T₁/₂)** az az idő, amely alatt  
a radioaktív atommagok **fele elbomlik**.

Fontos:
- nem függ a kezdeti mennyiségtől
- minden izotópra állandó

---

## Bomlástörvény
A megmaradó atomok száma idő függvényében:

N(t) = N₀ · (1/2)^(t / T₁/₂)

ahol:
- N₀ – kezdeti atomok száma
- N(t) – megmaradó atomok száma
- t – eltelt idő
- T₁/₂ – felezési idő

---

## Tipikus számolás – hány atom marad?

### Példa
Egy izotóp felezési ideje:  
T₁/₂ = 5 év  

Kezdetben:
N₀ = 800 atom

Mennyi marad **15 év múlva**?

### Megoldás
15 év = 3 felezési idő

Minden felezésnél feleződik:
- 1. felezés: 800 → 400
- 2. felezés: 400 → 200
- 3. felezés: 200 → 100

### Eredmény
**15 év után 100 atom marad**

---

## Tipikus kérdés – mennyi idő telt el?

### Példa
Kezdetben 400 atom volt, most 50 maradt.  
T₁/₂ = 4 év

### Megoldás
400 → 200 → 100 → 50  
Ez **3 felezés**

Idő:
t = 3 · 4 év = **12 év**

---

## Gyors ellenőrző táblázat

| Felezések száma | Megmaradó rész |
|----------------|---------------|
| 0              | N₀            |
| 1              | N₀ / 2        |
| 2              | N₀ / 4        |
| 3              | N₀ / 8        |
| n              | N₀ / 2ⁿ       |

---

## Vizsgatipp
👉 Ha **egész számú felezés van**, ne képletezz,  
👉 **lépcsőzetesen felezz**, gyorsabb és biztosabb.