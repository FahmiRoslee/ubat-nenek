---
keppra_500mg: 0
norvasc_5mg: 30
trajenta_5mg: 30
cavsamir_800g: 60
iberet_folic: 30
concor_2_5mg: 30
atorvastatin_20mg: 30
calcelar_25mg: 30
---

# 💊 Senarai & Jadual Ubat Nenek

## 📅 Jadual Harian (Daily Intake)

### 🌅 PAGI
*   **Keppra (Levetiracetam) 500mg** : 1 tablet *(Status: Habis)*
*   **Norvasc 5mg** : 1 tablet
*   **Trajenta 5mg** : 1 tablet
*   **Cavsamir 800g** : 2 tablet

### ☀️ TENGAHARI
*   **Iberet Folic 500mg** : 1 tablet

### 🌌 MALAM
*   **Concor 2.5mg** : 1 tablet
*   **Atorvastatin 20mg** : 1 tablet
*   **Cavsamir 800g** : 2 tablet
*   **Calcelar 25mg (Tulang)** : 2 tablet

---

## 📊 Baki Stok Ubat (Stock Tracker)

| Nama Ubat | Waktu Ambil | Baki Stok (Pills) | Tambah (+1) | Kurang (-1) |
| :--- | :--- | :--- | :--- | :--- |
| **Keppra 500mg** | Pagi | `INPUT[number:keppra_500mg]` | `BUTTON[tambah_keppra]` | `BUTTON[kurang_keppra]` |
| **Norvasc 5mg** | Pagi | `INPUT[number:norvasc_5mg]` | `BUTTON[tambah_norvasc]` | `BUTTON[kurang_norvasc]` |
| **Trajenta 5mg** | Pagi | `INPUT[number:trajenta_5mg]` | `BUTTON[tambah_trajenta]` | `BUTTON[kurang_trajenta]` |
| **Cavsamir 800g** | Pagi & Malam | `INPUT[number:cavsamir_800g]` | `BUTTON[tambah_cavsamir]` | `BUTTON[kurang_cavsamir]` |
| **Iberet Folic 500mg** | Tengahari | `INPUT[number:iberet_folic]` | `BUTTON[tambah_iberet]` | `BUTTON[kurang_iberet]` |
| **Concor 2.5mg** | Malam | `INPUT[number:concor_2_5mg]` | `BUTTON[tambah_concor]` | `BUTTON[kurang_concor]` |
| **Atorvastatin 20mg** | Malam | `INPUT[number:atorvastatin_20mg]` | `BUTTON[tambah_atorvastatin]` | `BUTTON[kurang_atorvastatin]` |
| **Calcelar 25mg** | Malam | `INPUT[number:calcelar_25mg]` | `BUTTON[tambah_calcelar]` | `BUTTON[kurang_calcelar]` |

---

### Konfigurasi Butang (Meta-Bind Buttons)

```meta-bind-button
id: tambah_keppra
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: keppra_500mg
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_keppra
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: keppra_500mg
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_norvasc
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: norvasc_5mg
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_norvasc
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: norvasc_5mg
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_trajenta
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: trajenta_5mg
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_trajenta
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: trajenta_5mg
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_cavsamir
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: cavsamir_800g
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_cavsamir
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: cavsamir_800g
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_iberet
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: iberet_folic
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_iberet
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: iberet_folic
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_concor
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: concor_2_5mg
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_concor
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: concor_2_5mg
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_atorvastatin
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: atorvastatin_20mg
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_atorvastatin
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: atorvastatin_20mg
    evaluate: true
    value: "x - 1"
```

```meta-bind-button
id: tambah_calcelar
label: "+"
style: primary
hidden: false
actions:
  - type: updateMetadata
    bindTarget: calcelar_25mg
    evaluate: true
    value: "x + 1"
```

```meta-bind-button
id: kurang_calcelar
label: "-"
style: destructive
hidden: false
actions:
  - type: updateMetadata
    bindTarget: calcelar_25mg
    evaluate: true
    value: "x - 1"
```
