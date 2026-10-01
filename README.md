# Praktikum 2: HTML Lanjutan - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 2 Pemrograman Web.

## Identitas Mahasiswa

| Keterangan      | Data                           |
| --------------- | ---------------                |
| **Nama**        | noel marihot tampubolon        |
| **Kelas**       | I251D                          |
| **NIM**         | 312510419                      |
| **Mata Kuliah** | Pemrograman Web                |

---

## 1. Struktur File

Struktur file pada praktikum ini adalah sebagai berikut:

## Struktur Folder Proyek

```
Lab2Web/
├── index.html
├── biodata.html
├── media/
│   ├── audio.mp3
│   └── video.mp4
└── README.md
```
<img width="222" height="222" alt="Screenshot 2026-10-01 153956" src="https://github.com/user-attachments/assets/ba1168a6-0db7-40f3-8019-9f906b9a7051" />



---
## Langkah-Langkah Praktikum

### 1. Membuat Tabel Data Mahasiswa

Pada langkah ini, kita membuat tabel dasar menggunakan elemen `<table>`, `<tr>`, `<th>`, dan `<td>` dengan atribut `border="1"` untuk menyajikan data mahasiswa ke dalam bentuk baris dan kolom.

<img width="830" height="282" alt="Screenshot 2026-10-01 154425" src="https://github.com/user-attachments/assets/e56c11e8-f29a-4060-9369-2ebb7e98632d" />


<img width="431" height="146" alt="Screenshot 2026-10-01 154457" src="https://github.com/user-attachments/assets/5db3b93c-4768-436e-bb2b-b201cc8367c6" />


### 2. Mengembangkan Tabel dengan `thead`, `tbody`, dan `tfoot`

Menyusun struktur tabel yang lebih kompleks dan rapi dengan membaginya ke dalam bagian kepala (`<thead>`), badan (`<tbody>`), dan kaki tabel (`<tfoot>`), serta menggunakan elemen `<caption>` dan atribut `colspan` untuk menggabungkan sel.

<img width="693" height="193" alt="Screenshot 2026-10-01 154708" src="https://github.com/user-attachments/assets/202161b5-84fa-4d38-8227-d44179447e69" />

<img width="251" height="118" alt="Screenshot 2026-10-01 154719" src="https://github.com/user-attachments/assets/f76108a6-d67c-4580-9777-703a6e9c1e8a" />

### 3. Membuat Form Registrasi Mahasiswa

Membuat form interaktif menggunakan elemen `<form>` beserta elemen input standar seperti teks, email, password, dan tanggal lahir (`type="date"`), dilengkapi tombol submit dan reset.

<img width="558" height="258" alt="Screenshot 2026-10-01 154926" src="https://github.com/user-attachments/assets/0e1769cc-fe01-4fb5-b7a1-19d02d77c7ad" />

<img width="566" height="374" alt="Data dan Form Registrasi Mahsiswa(1)" src="https://github.com/user-attachments/assets/c6e6ee93-5c6a-4364-8a0f-231cc212fc2c" />



### 4. Radio Button dan Checkbox

Menambahkan elemen pilihan lanjutan berupa *radio button* (`type="radio"`) untuk pilihan tunggal (seperti jenis kelamin) dan *checkbox* (`type="checkbox"`) untuk pilihan ganda (seperti keahlian).

<img width="452" height="95" alt="Screenshot 2026-10-01 155341" src="https://github.com/user-attachments/assets/d1d0eb3d-6852-4745-b43a-582e395c36aa" />

<img width="591" height="229" alt="Data dan Form Registrasi Mahsiswa(2)" src="https://github.com/user-attachments/assets/30cf63f7-6632-4a04-9c2a-5ac9bfa6d06f" />




### 5. Select dan Textarea

Menambahkan elemen dropdown pilihan menggunakan `<select>` dan `<option>`, serta kotak teks multi-baris menggunakan `<textarea>` untuk alamat.

<img width="562" height="208" alt="Screenshot 2026-10-01 155739" src="https://github.com/user-attachments/assets/65f07015-5f6c-40d3-b66e-21590cfcbc5c" />

<img width="775" height="318" alt="Data dan Form Registrasi Mahsiswa(3)" src="https://github.com/user-attachments/assets/046928f8-e987-494e-8325-4de6bcdfdf03" />

### 6. Validasi Form Dasar

Menerapkan atribut validasi bawaan HTML seperti `required`, `minlength`, `min`, dan `max` pada elemen form untuk memastikan input pengguna valid sebelum dikirim.


<img width="775" height="318" alt="Data dan Form Registrasi Mahsiswa(3)" src="https://github.com/user-attachments/assets/13a4b645-e6da-4f8a-93fb-bbe24dad4506" />


<img width="636" height="242" alt="Screenshot 2026-10-01 160050" src="https://github.com/user-attachments/assets/87ee6d66-638c-42b9-8742-1cb9511f25d1" />


### 7. Membuat Halaman Semantic HTML

Menyusun struktur tata letak halaman web yang lebih bermakna dan terstandar menggunakan elemen semantik seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`.


<img width="787" height="417" alt="Screenshot 2026-10-01 160529" src="https://github.com/user-attachments/assets/c25016b5-0153-4bc2-b32a-f4a7fbb38d74" />


<img width="532" height="305" alt="Screenshot 2026-10-01 160556" src="https://github.com/user-attachments/assets/2852e694-9732-4e12-9521-b76229f61c32" />

### 8. Menambahkan Multimedia

Menyisipkan file media berupa audio (`<audio>`) dan video (`<video>`) ke dalam halaman web dengan kontrol pemutaran (`controls`) serta mengambil sumber file dari folder `media/`.


<img width="481" height="156" alt="Screenshot 2026-10-01 160715" src="https://github.com/user-attachments/assets/bcb95426-425a-4443-8c47-663c5a003415" />


<img width="492" height="776" alt="Screenshot 2026-10-01 160840" src="https://github.com/user-attachments/assets/92d61c5d-644d-47c5-b73d-6c4301c42a6a" />


### 9. Proyek Mini: Form Biodata Mahasiswa

Menggabungkan seluruh materi yang telah dipelajari—meliputi struktur semantik, tabel data, form registrasi lengkap dengan validasi, hingga elemen multimedia—kedalam satu halaman web proyek mini (`biodata.html`).



<img width="597" height="657" alt="Screenshot 2026-10-01 161137" src="https://github.com/user-attachments/assets/28d67865-c7b7-4ebf-81d2-9a3e4932f6d2" />


<img width="612" height="236" alt="Screenshot 2026-10-01 161152" src="https://github.com/user-attachments/assets/f49b2bc5-4cd1-44f9-b692-c632fbbcbb04" />


<img width="388" height="1080" alt="Biodata Mahasiswa(1)" src="https://github.com/user-attachments/assets/8846c8cb-78c1-4b78-9fe5-7d4a39c03eb6" />

