# DOC.md

## 📌 Deskripsi Aplikasi
Aplikasi **CV Mahasiswa** adalah Single Page Application (SPA) berbasis **ReactJS** yang menampilkan Curriculum Vitae digital mahasiswa. Aplikasi mengambil data dari file `dataMahasiswa.json`, sehingga perubahan data dapat dilakukan tanpa menyentuh kode inti.

Fitur utama:
- Menampilkan foto profil, nama, headline, dan biodata.
- Menampilkan daftar keahlian (skills) lengkap dengan ikon/logo.
- Menampilkan pengalaman (experience) dan pendidikan (education).
- Struktur SPA ringan dan responsif.
- Sudah dideploy ke Vercel dan dapat diakses publik.

---

## 🚀 Cara Menjalankan Aplikasi Secara Lokal

### 1. Clone Repository
```bash
git clone git@github.com:tif1336/single-page-application-reactjs-untuk-cv-mahasiswa-LatifWithoutH.git
```

### 2. Masuk ke Direktori Project
```bash
cd single-page-application-reactjs-untuk-cv-mahasiswa-LatifWithoutH
```

### 3. Install Dependency
```bash
npm create vite@latest cv-mahasiswa -- --template react
```

### 4. Jalankan Development Server
```bash
npm run dev
```

### 5. Buka di Browser
http://localhost:5173

---

## 🌐 Link Deployment
Aplikasi versi live dapat diakses pada:

**https://cv-mahasiswa-l200239190.vercel.app/**

---

## 📸 Screenshot Tampilan
Screenshot pada folder:

```
screenshots/
│── profile.png
│── skills.png
└── experience.png
```


Tampilan Profile

![Screenshot Profile](./screenshot/profile.png)

Tampilan Skills

![Screenshot Skills](./screenshot/skills.png)

Tampilan Experience

![Screenshot Experience](./screenshot/experience.png)

---

## 📂 Struktur Folder
```
MY-REACT_CV/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── experience.jsx
│   │   ├── profile.jsx
│   │   └── skill.jsx
│   ├── data/
│   │   └── dataMahasiswa.json
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
├── DOC.md
└── README.md
```

---

## 📦 Teknologi yang Digunakan
- ReactJS (Vite)
- JavaScript
- CSS 
- JSON untuk sumber data
- Vercel Deployment

---

## 🧑‍💻 Developer
**Aziz Ilham Rahman**  
NIM: **L200230274**  
Program Studi: **Teknik Informatika – Universitas Muhammadiyah Surakarta**
