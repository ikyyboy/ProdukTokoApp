# 🛒 ProdukTokoApp

Aplikasi **Daftar Produk Toko** merupakan aplikasi desktop berbasis Java yang dikembangkan menggunakan JavaFX dan Maven. Aplikasi ini dibuat untuk memenuhi tugas individu mata kuliah **Pemrograman Lanjut** dengan menerapkan konsep Object-Oriented Programming (OOP).

Aplikasi memungkinkan pengguna untuk menambahkan produk, melihat daftar produk, mencari produk berdasarkan nama, serta melihat detail produk yang dipilih.

## ✨ Fitur Aplikasi

- **Tambah Produk** — Menambahkan produk baru dengan informasi nama, kategori, dan harga.
- **Daftar Produk** — Menampilkan seluruh produk dalam bentuk tabel.
- **Pencarian Produk** — Mencari produk berdasarkan nama.
- **Detail Produk** — Menampilkan informasi lengkap dari produk yang dipilih.
- **Validasi Input** — Memastikan nama produk tidak kosong dan harga harus lebih dari nol.
- **Kategori Produk** — Menyediakan dua kategori, yaitu Makanan dan Minuman.
- **Kode Produk Otomatis** — Setiap produk mendapatkan kode unik secara otomatis.

## 🛠️ Teknologi yang Digunakan

| Teknologi | Keterangan |
|---|---|
| Java | Bahasa pemrograman |
| JavaFX 21 | Framework antarmuka pengguna |
| Maven | Build dan dependency management |
| FXML | Struktur tampilan aplikasi |
| CSS | Styling antarmuka |
| JDK 17 | Java Development Kit |

## 📂 Struktur Proyek

```text
ProdukTokoApp/
├── pom.xml
└── src/
    └── main/
        ├── java/
        │   └── kelas/
        │       ├── MainApp.java
        │       ├── Navigator.java
        │       ├── model/
        │       │   └── Produk.java
        │       ├── data/
        │       │   └── DataProduk.java
        │       └── controller/
        │           ├── FormController.java
        │           ├── DaftarController.java
        │           └── DetailController.java
        │
        └── resources/
            └── kelas/
                ├── form.fxml
                ├── daftar.fxml
                ├── detail.fxml
                └── styles/
                    └── app.css
```

## 🧩 Konsep OOP yang Diterapkan

Aplikasi ini menerapkan beberapa konsep pemrograman berorientasi objek:

1. **Class dan Object** — Class `Produk` digunakan sebagai cet
