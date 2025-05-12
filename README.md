# DeepSeek Chat Client

Selamat datang di repository **DeepSeek Chat Client**! 🎉

Aplikasi ini adalah klien chat sederhana berbasis web untuk berinteraksi dengan API DeepSeek. Dengan antarmuka yang bersih dan responsif, kamu bisa mengirim pertanyaan (prompt) ke DeepSeek dan melihat balasan langsung di halaman.

## Fitur Utama

* 🔑 **Autentikasi API**: Masukkan kunci API DeepSeek kamu untuk otorisasi.
* 💬 **Chat Interaktif**: Kirim prompt dan terima balasan dalam format Markdown yang lebih menarik.
* 📜 **Riwayat Percakapan**: Simpan semua chat di `localStorage`, bisa dihapus dan dipanggil ulang kapan saja.
* 🛠️ **Opsi Lanjutan**: Atur tipe respons, jumlah `max_tokens`, dan `temperature` sesuai kebutuhan.
* 🖥️ **Desain Responsif**: Dibangun dengan Bootstrap 5 dan font Inter, nyaman di desktop maupun mobile.

## Instalasi & Penggunaan

1. **Clone** repository ini:

   ```bash
   git clone https://github.com/username/deepseek-chat-client.git
   cd deepseek-chat-client
   ```

2. **Buka** file `index.html` di browser favorit kamu.

3. **Masukkan** kunci API pada kolom "Kunci API".

4. **Ketik** pesan di kolom "Prompt Anda" lalu klik **Kirim**.

5. **Nikmati** balasan dari DeepSeek! 🎈

## Struktur Proyek

```
├── index.html       # Halaman utama klien chat
└── README.md        # Dokumentasi proyek ini
```

> Tidak ada file lain—cukup buka `index.html`, dan kamu siap terhubung ke DeepSeek.

## Konfigurasi Lanjutan

* **Tipe Respon**: Pilih `Default`, `Kode`, atau `Chat` sesuai tujuan.
* **Max Tokens**: Batas maksimal token di respon API.
* **Temperature**: Atur tingkat kreativitas model (0.0–1.0).

Semua opsi ini dapat diakses melalui tombol **Opsi Lanjutan**.

## Kontribusi

Jika kamu ingin berkontribusi, silakan:

1. Buat fork repository ini.
2. Buat branch baru: `git checkout -b fitur-baru`.
3. Tambahkan fitur atau perbaiki bug.
4. Commit perubahan: `git commit -m "Menambahkan fitur X"`.
5. Push ke branch kamu: `git push origin fitur-baru`.
6. Buat Pull Request di GitHub.

## Lisensi

Proyek ini dirilis di bawah lisensi **MIT License**. Silakan cek file `LICENSE` untuk detail.

---

Terima kasih sudah mampir! Semoga DeepSeek Chat Client ini bermanfaat untuk kamu bereksperimen dengan model AI. 🚀
