# Mental Health V2

**Mental Health V2** adalah platform berbasis web yang dirancang khusus untuk membantu mahasiswa meningkatkan kesehatan mental melalui program *mindfulness* yang terstruktur.

---

## 🎯 Fitur Utama
- **Autentikasi & Screening Wajib**: Login dan screening awal sebelum mengakses program.
- **Program Mindfulness**:
  - Ringkasan materi
  - Audio pembelajaran
  - Gambar pendukung
  - Jurnal harian
  - Latihan interaktif
- **Artikel Edukatif**: Berisi informasi kesehatan mental yang relevan.
- **Fitur Admin (CRUD)**:
  - Tambah, edit, hapus data
  - Pantau aktivitas peserta
  - Kelola konten program

---

## 🛠️ Teknologi
- **Frontend**: Bootstrap
- **Backend**: Flask (Python)
- **Database**: MongoDB

---

## 📌 Diagram Alur Program

```mermaid
flowchart TD
    A[User Buka Website] --> B[Login]
    B --> C[Screening Awal]
    C -->|Lulus Screening| D[Masuk ke Program Mindfulness]
    D --> E[Materi: Ringkasan, Audio, Gambar, Jurnal]
    E --> F[Artikel Edukatif]
    F --> G[Program Selesai]
    C -->|Tidak Lulus Screening| H[Rekomendasi Bacaan]
