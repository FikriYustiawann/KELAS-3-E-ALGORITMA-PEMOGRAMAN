# 🧮 Logika Matematika - Sistem Remedial

## 📝 **Deskripsi Masalah**
Di sebuah sekolah, terdapat aturan mengenai ujian remedial matematika. Siswa yang mendapatkan nilai kurang dari 75 harus mengikuti ujian remedial, sedangkan siswa yang mendapatkan nilai 75 atau lebih tidak perlu mengikuti remedial.
Masalah ini dapat digunakan untuk menerapkan logika matematika dalam menentukan suatu keputusan berdasarkan kondisi yang diberikan. Program akan menerima nilai matematika siswa sebagai input, kemudian mengevaluasi apakah nilai tersebut kurang dari 75 atau tidak. Berdasarkan hasil evaluasi tersebut, program akan menentukan apakah siswa perlu mengikuti ujian remedial atau tidak.

## 📥 **Input-Proses-Output**
**Input:** Nilai ujian matematika yang diperoleh siswa.

**Proses:** Program membandingkan nilai siswa dengan batas nilai 75. Jika nilai kurang dari 75, siswa perlu mengikuti remedial. Jika nilai 75 atau lebih, siswa tidak perlu mengikuti remedial.

**Output:** Apakah siswa perlu mengikuti remedial atau tidak.

## 💻 **Pseudocode**
```text
INPUT nilai

IF nilai < 75 THEN
    OUTPUT "Siswa harus mengikuti ujian remedial"
ELSE
    OUTPUT "Siswa tidak perlu mengikuti ujian remedial"
END IF
```
## 📊 **Flowchart**

```mermaid
%%{init: {
  "themeVariables": {
    "fontSize": "12px"
  },
  "flowchart": {
    "nodeSpacing": 15,
    "rankSpacing": 20,
    "padding": 8
  }
}}%%

flowchart TD
    A([START]) --> B[/INPUT nilai/]
    B --> C{Apakah nilai < 75?}

    C -->|Ya| D[/OUTPUT<br/>"Siswa harus mengikuti<br/>ujian remedial"/]
    C -->|Tidak| E[/OUTPUT<br/>"Siswa tidak perlu mengikuti<br/>ujian remedial"/]

    D --> F([END])
    E --> F

    style A fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
    style B fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d
    style C fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f
    style D fill:#fee2e2,stroke:#dc2626,stroke-width:2px,color:#7f1d1d
    style E fill:#e0e7ff,stroke:#4f46e5,stroke-width:2px,color:#312e81
    style F fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
```

## 🧪 **Test Case**
| Test Case | Input Nilai | Kondisi | Hasil yang Diharapkan |
|---|---:|---|---|
| 1 | 60 | Nilai < 75 | Siswa harus mengikuti ujian remedial |
| 2 | 80 | Nilai ≥ 75 | Siswa tidak perlu mengikuti ujian remedial |

## 🐍 **Implementasi Python**

Implementasi program dibuat menggunakan Python dan dijalankan melalui Visual Studio Code,
Source code dapat dilihat pada **[main.py](main.py)**.

## 📸 **Hasil Pengujian**
Program telah berhasil diuji menggunakan dua nilai, yaitu 60 dan 80 sesuai dengan test case, dan menghasilkan output sesuai dengan kondisi yang telah ditentukan.

<img width="720" height="450" alt="Tangkapan Layar 2026-09-01 pukul 19 09 46" src="https://github.com/user-attachments/assets/3cc6b4bd-73de-49ec-bbaa-a56f79a05edf" />

