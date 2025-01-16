# 🎧 SpotifyClust

**Yo!** repo ini berisi sebuah sistem rekomendasi musik pada _spotify_ yang dibagun dengan
menggunakan clustering _unsupervised machine learning based_. Dataset yang digunakan berasal dari
kaggle tentunya ([Spotify Dataset](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset)).
input daftar musik, durasi, tahun rilis dari user didengarkan user menggunakan clustering untuk
membaca pola yang ada pada dataset.

## 📝 Requirements

Untuk mendukung kelancaran installasi pastikan sudah memenuhi hal-hal berikut:

- Menggunakan **`Python 3.9.12`** (versi lain tidak direkomendasikan)

## ❓ Parameter

- Parameter yang digunakan untuk sebuah input merupakan sebuah array yang berisi judul lagu, tahun
  rilis, nama penyanyi.

- Ouput sistem akan memeberikan beberapa rekomendasi lagu yang memilki kemiripan dari input user
  berdasarkan dataset yang tersedia.

## 🗝️ SPOTIFY DASHBOARD

## ⚙️ Konfigurasi Installasi

1. Clone Repository

   ```bash
   git clone https://github.com/Hazz-i/SpotifyClust.git
   ```

2. Masuk Directory Utama

   ```bash
   cd SpotifyClust
   ```

3. Buat virtual environment

   ```bash
   python -m venv [nama environment]
   ```

4. Aktifkan virtual environment

   ```bash
   # mac / git bash
   source ./[nama environment]/bin/scripts/activate

   # powershell
   ./[nama environment]/bin/scripts/activate
   ```

5. Install dependesi

   ```bash
   pip install -r requirements.txt
   ```

6. Jalankan script

   ```bash
   # python script
   streamlit run dashboard.py

   # open jupyter
   jupyter-notebook .
   ```

---

<p>Semangat ga semangat umurmu tetep nambah 🙏</p>
