# Microprosessor.drawio
# Multiprocessor Architecture Diagrams

## 📚 Deskripsi
Repository ini berisi diagram arsitektur untuk:
- **Multiple Processor Architecture** (Master-Slave Model)
- **Symmetric Multiprocessor Architecture** (Shared Bus Model)

Diagram dibuat menggunakan **draw.io** untuk memvisualisasikan hubungan antar CPU, Memory, dan I/O dalam kedua model multiprosesor.

## 🛠️ Cara Membuka Diagram
1. Buka [draw.io](https://app.diagrams.net/).
2. Pilih **File → Import From → Device**.
3. Upload file `file.drawio`.
4. Diagram siap untuk diedit atau dilihat!

## 📁 Struktur File
- `Multiprocessor Architecture.drawio` — File diagram utama dalam format `.drawio` (XML).

## 🖼️ Preview Diagram
![ChatGPT Image Apr 26, 2025, 02_20_03 PM](https://github.com/user-attachments/assets/d58bebb9-3183-405b-a6a3-b4080eeddce2)


**Multiple Processor Architecture**  
- Sistem ini memiliki struktur **Master-Slave**.
- **Master CPU** bertanggung jawab penuh dalam mengendalikan semua operasi.
- **Slave CPU** hanya melaksanakan perintah dari Master CPU tanpa kemampuan pengolahan independen.
- **Memory** dan **I/O Devices** diakses melalui perintah dari Master CPU.
- Kelemahan utama: jika Master CPU gagal, seluruh sistem bisa terganggu.

**Symmetric Multiprocessor Architecture**  
- Semua **CPU setara** dan memiliki hak akses langsung ke **Memory** dan **I/O**.
- Semua CPU terhubung melalui **Shared Bus** yang digunakan bersama-sama.
- Keunggulan: kinerja lebih stabil dan cepat karena tugas dapat dibagi rata ke semua CPU.
- Tantangan: kemungkinan terjadi **bus contention** (persaingan akses jalur bersama).

---

## 📈 Perbandingan Multiple Processor vs Symmetric Multiprocessor

| Aspek                    | Multiple Processor                 | Symmetric Multiprocessor        |
|---------------------------|-------------------------------------|----------------------------------|
| Struktur                  | Master-Slave                       | Semua CPU setara                 |
| Akses ke Memory/I/O       | Melalui Master CPU                 | Langsung oleh semua CPU           |
| Kelebihan                 | Struktur sederhana                 | Efisiensi tinggi, fleksibel       |
| Kekurangan                | Bottleneck di Master CPU           | Risiko bus contention             |
| Contoh Penggunaan         | Embedded Systems, sistem lama      | Server modern, workstation multitasking |

---



## 📜 Lisensi
Lisensi bebas digunakan untuk keperluan edukasi.  
(Catatan: Kamu bisa tambahkan lisensi spesifik seperti MIT, GPL, atau bebas hak cipta sesuai kebutuhan.)

---

