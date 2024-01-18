# Pertemuan ke 6

## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Intan Virginia Aulia Putri |
| **NIM** | 312310657 |
| **Kelas** | TI.23.A.6 |
| **Mata Kuliah** | Bahasa Pemrograman |

### Tugas Latihan
- Buat repository Praktikum3
- Buat kode program untuk menghitung luas dan keliling lingkaran menggunakan Python
- Buat penjelasan setiap latihannya pada file README.md
- Sertakan flowchart dan penjelasan program dan screenshot hasil eksekusi program
- Simpan project Praktikum hari ini ke repository server (github)

### Buat kode program untuk menghitung luas dan keliling lingkaran menggunakan Python
``` Python
import math

# Mengambil input dari pengguna untuk jari-jari lingkaran
r = float(input("Masukkan jari-jari lingkaran: "))

# Menghitung luas lingkaran
luas = math.pi * (r ** 2)

# Menghitung keliling lingkaran
keliling = 2 * math.pi * r

# Menampilkan hasil
print(f"Luas lingkaran: {luas:.2f}")
print(f"Keliling lingkaran: {keliling:.2f}")
```

### Penjelasan
- `import math`: Ini adalah pernyataan untuk mengimpor modul math yang menyediakan fungsi matematika, termasuk nilai π (pi)
- `r = float(input("Masukkan jari-jari lingkaran: "))`: Ini adalah baris kode yang meminta pengguna untuk memasukkan nilai jari-jari lingkaran. Fungsi input digunakan untuk menerima masukan dari pengguna, dan float() digunakan untuk mengonversi masukan menjadi tipe data float
- `luas = math.pi * (r ** 2)`: Ini adalah baris kode yang menghitung luas lingkaran menggunakan formula π * r^2. Nilai π diambil dari modul math
- `keliling = 2 * math.pi * r`: Ini adalah baris kode yang menghitung keliling lingkaran menggunakan formula 2 * π * r. Kembali, nilai π diambil dari modul math
- `print(f"Luas lingkaran: {luas:.2f}")`: Ini adalah baris kode yang mencetak hasil perhitungan luas lingkaran dengan dua angka desimal.
- `print(f"Keliling lingkaran: {keliling:.2f}")`: Ini adalah baris kode yang mencetak hasil perhitungan keliling lingkaran dengan dua angka desimal.

#### Tampilan output
![gambar 1](screenshot/ss1.png)

#### Flowchart
![gambar 2](screenshot/ss2.png)
