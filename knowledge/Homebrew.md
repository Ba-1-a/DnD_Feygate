# Homebrew Rules – Campaign DnD Feygate

Dokumen ini berisi aturan-aturan *homebrew* yang disepakati bersama antara pemain (B) dan DM (asisten AI) sepanjang campaign.  
Aturan ini mengikat dan menjadi dasar untuk semua sesi selanjutnya.

---

## 🗡️ Kemampuan Kustom Karakter

### 1. Arcane Sprint
- **Efek:** +15 kaki kecepatan bergerak, durasi 1 jam. Bisa ditumpuk dengan *Longstrider* atau efek serupa.
- **Downside:** Selama durasi, karakter **tidak dapat menggunakan aksi Hide** (Stealth). Jejak energi Arcana yang tertinggal membuatnya mudah terdeteksi.
- **Penggunaan:** Tanpa batas per hari (tidak memerlukan *spell slot*). Diaktifkan sebagai **Action**.

### 2. Arcane Edge (Permanen)
- **Efek:** Legam (pedang B) menjadi senjata **magical permanen**. Dapat mem-bypass **resistansi fisik non-magical** dan **imunitas fisik non-magical**.
- **Catatan:** Tidak memberikan bonus +1/+2/+3. Hanya sifat magical.

### 3. Panah Arcanum (*Pengetahuan Fey Panah Arcanum*)
- **Efek:** Sebagai **Bonus Action**, B dapat menyalurkan energi Arcana ke 1 panah biasa. Panah tersebut menjadi magical selama 1 menit.
- **Batasan:** Panah ini hanya efektif melawan makhluk yang memiliki **imunitas terhadap physical damage non-magical** (tidak berpengaruh pada resistansi biasa).
- **Penggunaan:** Tanpa batas.

### 4. Returning Legam
- **Efek:** Legam dapat dilempar sebagai serangan jarak jauh (improvised weapon, 1d4 damage, range 20/60 ft). Setelah dilempar, pedang akan kembali ke tangan B pada akhir giliran.
- **Biaya:** Diperoleh melalui ritual 1 hari dengan Elder, mengorbankan sepotong ingatan (tentang "rumah").

### 5. Legam Bercahaya (On-Off)
- **Efek:** Bilah Legam dapat berpendar biru pucat (warna Jantung) atau padam total.
- **Aktivasi:** Sebagai *free action* atau *Bonus Action* (tergantung situasi). Cahaya setara obor (radius terang 20 ft, redup 40 ft).

---

## 🛡️ Aturan Crafting & Tools

### 1. Jammer Stone
- **Deskripsi:** Batu kecil dengan ukiran simbol kuno. Berfungsi sebagai peredam/pengganggu deteksi sihir.
- **Cara Kerja:** Bekerja sesuai niat pemasang (bisa untuk menyembunyikan area, mengirim pesan, atau sebagai jebakan/distraksi).
- **Pembuatan:** Butuh batu permata murahan (akik, kuarsa) + Woodcarver's Tools + 30 menit per batu.

### 2. Racun dan Herbal
- Sistem yang digunakan adalah **homebrew berdasarkan Herbalism Kit** (bukan Poisoner's Kit baku).
- Tanaman umum: Jelatang, Bloodmoss, Sunpetal, Bittercap, dll. (lihat `knowledge/herbs.md` jika ada).
- Racun pelumpuh DC 11 atau DC 13 (jarahan) berlaku *Constitution save* setiap ronde.

### 3. Armor & Bracers dari Monster
- Kulit Owlbear dapat dijadikan armor (setara Studded Leather, AC 12 + DEX).
- Bracers dari taring Worg + kulit Owlbear: 1x per long rest, kurangi damage 1d4 dari serangan fisik (naratif, bukan mekanis penuh).

---

## 🎲 Prosedur Roll Dadu (Disepakati)

- Untuk semua roll yang memengaruhi hasil (attack, save, skill, damage), **DM wajib menggunakan API `rolz.org`**.
- Contoh: `https://rolz.org/api/?1d20.json`, `https://rolz.org/api/?2d20kh1.json` (advantage), `https://rolz.org/api/?2d6+3.json`.
- Hasil API digunakan apa adanya, tidak boleh dimanipulasi. Pemain dapat memverifikasi dengan membuka tautan.
- Untuk roll non-kritis (misal damage setelah dipastikan kena), DM dapat menggunakan nilai rata-rata atas persetujuan pemain.

---

## 🧙‍♂️ Aturan Lain

### 1. Hit Points (HP)
- Sistem yang digunakan: **nilai rata-rata** (bukan roll) untuk setiap level.  
  Formula: `(maks level 1) + (rata-rata per level × (level-1)) + (CON mod × level)`.
- Tidak ada roll untuk HP. Ini untuk konsistensi dan menghindari variasi ekstrem.

### 2. Called Shot (Tembak bagian tubuh tertentu)
- Diizinkan, tapi dengan **disadvantage** pada attack roll. DM dapat memberikan efek naratif sesuai situasi (misal: patah kaki, buta sementara). Tidak ada bonus damage.

### 3. Hide setelah Serangan Jarak Dekat (Terjang/Tikam)
- Diizinkan dalam campaign ini sebagai hasil negosiasi dan keseimbangan.  
  Urutan: Serang (Action) → Hide (Bonus Action via Cunning Action) → Movement (30 ft).  
  *Tidak* dapat melakukan Disengage di giliran yang sama jika sudah menggunakan Hide.

---

## 📜 Perubahan & Kesepakatan
Aturan ini bersifat dinamis dan dapat ditambah/ubah berdasarkan kesepakatan bersama.  
Setiap perubahan akan dicatat di file ini dengan tanggal dan keterangan.

*Terakhir diperbarui: 14 Mei 2026*