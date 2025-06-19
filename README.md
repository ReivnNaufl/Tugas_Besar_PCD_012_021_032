# 👁️ Your Last Gaze

**Your Last Gaze** adalah game horor eksperimental berbasis _face detection_ menggunakan **MediaPipe Face Mesh**. Pemain hanya memiliki satu cara untuk bertahan hidup: **menutup mata**. Rasakan ketegangan saat objek-objek di kamar mulai bergetar dan bersiap menghadapi jumpscare.

## 🎮 Gameplay Overview

Dalam game ini, kamu bermain sebagai seseorang yang kesulitan tidur. Ketika objek di kamar mulai bergetar, itu adalah **pertanda jumpscare akan terjadi**. Satu-satunya cara untuk bertahan hidup adalah dengan **menutup matamu secepatnya**.

Jika kamu berhasil menutup mata sebelum jumpscare dimulai, kamu akan mendengar audio yang menandakan bahaya telah berlalu. Namun jika gagal... bersiaplah untuk akhir yang mengejutkan.

## 🛠️ Teknologi yang Digunakan

- [MediaPipe Face Mesh](https://google.github.io/mediapipe/) – untuk pelacakan mata real-time
- **OpenCV** – untuk pemrosesan gambar
- **FastAPI** – untuk backend python
- **React** – untuk tampilan frontend dan logika game  

## 📦 Instalasi & Menjalankan Game
### 1. Clone repository ini
```bash
git clone https://github.com/ReivnNaufl/Tugas_Besar_PCD_012_021_032.git
```
### 2. Ubah ke direktori frontend
```bash
cd 02_FastAPI_Interface/client
```
### 3. Download dependency frontend & build frontend
```bash
npm i
npm run build
```
### 4. Ubah ke direktori backend
```bash
cd ../server
```
### 5. Download dependency backend
```bash
pip install -r requirements.txt
```
### 6. Jalankan game
```bash
uvicorn app.main:app --reload
```
