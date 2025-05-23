

# 🌐 Web Portofolio - Abdulloh Mun'am

Ini adalah proyek web portofolio yang dibuat menggunakan Django sebagai tugas Ujian Tengah Semester (UTS) pada mata Server Side Programming. Website ini menampilkan informasi pribadi, karya-karya portofolio, serta info contact.

---

## 🛠️ Teknologi yang Digunakan

- Python 3.x
- Django 4.x
- HTML5
- Tailwind CSS
- Django
- File statis (gambar & CSS)

---

Berikut keterangan struktur proyek tanpa tampilan pohon (tree):

---

## 🗂️ Penjelasan Struktur Project

* **`manage.py`**: Skrip utama untuk menjalankan perintah Django (seperti `runserver`, `migrate`, dll).
* **`db.sqlite3`**: Basis data default yang digunakan oleh Django.
* **`portfolio_website/`**: Direktori utama untuk pengaturan Django seperti `settings.py`, `urls.py`, `wsgi.py`, dan `asgi.py`.
* **`blog/`**: Aplikasi Django untuk menampilkan artikel blog.
* **`contact/`**: Aplikasi Django untuk mengelola halaman dan form kontak.
* **`home/`**: Aplikasi Django untuk halaman utama (landing page), termasuk bagian hero, skills, dan lainnya.
* **`project/`**: Aplikasi Django yang menampilkan daftar proyek yang telah dibuat.
* **`static/`**: Berisi file statis seperti gambar dan file CSS hasil kompilasi dari Tailwind.
* **`templates/`**: Berisi file HTML yang digunakan untuk merender halaman web, termasuk `base.html` sebagai layout utama dan komponen seperti navbar, footer, dan section-section lainnya.

> Folder `__pycache__` dan file `.pyc` adalah file sementara yang dibuat secara otomatis oleh Python, dan bisa diabaikan atau dihapus dari repository.

---

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori atau download kode:**
   ```bash
   git clone https://github.com/username/portfolio.git
   cd portfolio

2. **Aktifkan virtual environment (opsional tapi disarankan):**

   ```bash
   python -m venv env
   source env/bin/activate  # Linux/macOS
   env\Scripts\activate     # Windows
   ```

3. **Install dependency:**

   ```bash
   pip install django
   ```

4. **Jalankan server Django:**

   ```bash
   python manage.py runserver
   ```

5. **Buka browser dan akses:**

   ```
   http://127.0.0.1:8000/
   ```

---

## 📄 Fitur Website

* **Homepage dengan Hero Section** – Menampilkan nama, foto, dan deskripsi singkat diri.
* **Project Showcase** – Menampilkan daftar proyek lengkap dengan gambar dan deskripsi.
* **Blog Section** – Artikel blog tentang teknologi, tips, atau pengalaman pribadi.
* **Contact Form** – Formulir untuk mengirim pesan secara langsung.
* **Responsive Design** – Tampilan responsif yang optimal di berbagai perangkat.
* **Routing antar halaman** – Navigasi terstruktur untuk Home, Blog, Project, dan Contact.
* **Django Admin** – Panel admin untuk mengelola konten blog, kontak, dan proyek.
* **Static Files Management** – Mengelola file gambar dan CSS dengan struktur rapi.
* **Tailwind CSS** – Styling modern dan konsisten menggunakan Tailwind.

---

## 📱 Responsif

Website ini mendukung tampilan di berbagai ukuran layar (mobile-friendly). Elemen akan menyesuaikan secara otomatis untuk pengalaman pengguna yang lebih baik.

---

## 👨‍🎓 Profil Pembuat

* **Nama**: Abdulloh Mun'am
* **NIM**: 23201292
* **Kelas**: C1

---

## 📚 Lisensi

Proyek ini dibuat hanya untuk keperluan pembelajaran dan tugas UTS. Bebas digunakan kembali dengan atribusi yang sesuai.
