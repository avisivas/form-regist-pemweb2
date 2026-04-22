# Form Registrasi Event

## Hasil Akhir
Bagian ini menampilkan tampilan utama dari form registrasi yang telah berhasil diimplementasikan.
![Hasil](/awal.png)
### Form Registrasi Event berisi:
- **Nama Lengkap (Text):** Input untuk nama pendaftar.  
- **Email (Email validation):** Input dengan validasi format email.  
- **Password (Min. 8 karakter):** Input password dengan keamanan minimal 8 karakter.  
- **Pilihan Kategori Event (Select):** Menu dropdown untuk memilih kategori event.  
- **Bio Singkat (Textarea):** Input deskripsi diri atau latar belakang pendaftar.  

## Tampilan Saat Validasi Error
![Hasil](/error.png)
Sistem akan memberikan feedback visual dan pesan peringatan jika input yang dimasukkan tidak sesuai dengan kriteria yang ditentukan.

### Kondisi Error yang Ditangani:

- **Nama:** Menampilkan pesan *"Nama harus diisi"* jika field kosong.  
- **Email:** Menampilkan pesan *"Format email tidak valid"* jika struktur email salah.  
- **Password:** Menampilkan pesan *"Password minimal 8 karakter"* jika terlalu pendek.  
- **Kategori Event:** Menampilkan pesan *"Pilih salah satu"* jika belum ada kategori yang dipilih.  
- **Bio:** Menampilkan pesan *"Bio harus diisi"* jika textarea kosong.  

## Fitur Tambahan
![Hasil](/valid.png)
- **Show/Hide Password:** Pengguna dapat melihat atau menyembunyikan password yang sedang diketik.  
- **Loading State:** Tombol akan berubah menjadi *"Loading..."* saat proses pengiriman data berlangsung untuk mencegah pengiriman ganda.  
