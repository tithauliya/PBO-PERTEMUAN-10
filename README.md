#  Penambahan Fitur Upload File CSV untuk Import Data pada Aplikasi Toko Roti Berbasis Java

## Deskripsi Proyek
Fitur utama yang dikembangkan adalah **Upload File CSV**, yang memungkinkan pengguna mengimpor data produk langsung dari file `.csv` ke dalam database PostgreSQL.  
Dengan fitur ini, proses input data menjadi lebih cepat, efisien, dan meminimalkan kesalahan manusia (*human error*).

## ⚙️ Langkah-Langkah Praktikum
1. **Mempersiapkan File CSV**  
   File CSV berisi data roti dengan kolom: `id_kue`, `nama_kue`, `harga`, dan `stock`.  
   Format CSV dipilih karena mudah dibuat melalui **Microsoft Excel** atau **Google Sheets**.
   <img width="578" height="802" alt="Screenshot 2025-10-21 144504" src="https://github.com/user-attachments/assets/cc3d7ec5-8934-4d28-b47f-34696d6eb8fd" />

3. **Menambahkan Tombol Upload di GUI**  
   Tombol **UPLOAD** ditambahkan pada form utama (`Tampilan.java`) agar pengguna bisa mengakses fitur langsung dari halaman utama.
   <img width="945" height="568" alt="Screenshot 2025-10-21 152557" src="https://github.com/user-attachments/assets/ee6a17dd-9ac9-44e1-b8f7-47341f45aefa" />

5. **Menambahkan Kode Upload CSV**
   <img width="989" height="969" alt="Screenshot 2025-10-21 144706" src="https://github.com/user-attachments/assets/56c4b6b6-d634-42f8-894c-00c5f30efd25" />
