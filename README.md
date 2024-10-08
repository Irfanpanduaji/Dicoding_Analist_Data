# Dicoding_Analist_Data

## Penulis
- **Nama:** Irfan Pandu Aji
- **Email:** ( panduaji7972@gmail.com )
- **MyProfil Dicoding:** [ https://www.dicoding.com/users/irfanaji/academies ]
- 
## Berkas
- `Proyek_Analisis_Data.ipynb`: Notebook Jupyter yang berisi analisis data.
- `dashboard/`: Direktori yang berisi aplikasi dashboard Streamlit.

## Cara Menjalankan
- Notebook Jupyter dapat dilihat langsung di GitHub atau dijalankan dalam lingkungan yang mendukung Jupyter Notebook Python.
- Dashboard Streamlit dapat dijalankan secara lokal dengan terlebih dahulu menavigasi ke direktori dashboard/ dan menjalankan perintah berikut:
cd dashboard
streamlit run dashboard.py

## Setup Environment - Anaconda
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

## Setup Environment - Shell/Terminal
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

## Menjalankan Aplikasi Streamlit
Pastikan Anda berada di folder dashboard terlebih dahulu sebelum menjalankan aplikasi Streamlit, karena file dashboard.py berada di dalam folder tersebut.
cd dashboard
streamlit run dashboard.py

Dengan menjalankan perintah di atas, dashboard akan terbuka di browser web Anda secara lokal.

## Cara menjalankan Streamlit dengan Localhost server anda
1. Unduh dataset yang tertera di atas dengan format .csv.
2. Jalankan kode (dashboard.py) ke dalam EDA (Exploratory Data Analysis) kesukaan Anda.
3. Instal Streamlit pada command prompt Anda dengan menjalankan:
pip install streamlit
4. Setelah instalasi selesai, navigasikan ke folder dashboard/ dan buka file (dashboard.py) dengan perintah berikut:
cd dashboard
streamlit run dashboard.py
5. Dashboard akan terlihat di browser web Anda secara lokal.

## Dashboard
Dashboard Streamlit mencakup fitur-fitur berikut:

1. Tampilan interaktif dari data mentah dan statistik ringkasan.
2. Visualisasi yang menjawab pertanyaan bisnis kunci:
- Bagaimana pola perubahan jumlah pengguna sepeda selama 6 bulan? Apakah ada tren tertentu yang muncul, dan pada periode mana dalam bulan tersebut pengguna sepeda mencapai angka tertinggi?
- Berdasarkan data yang ada, bagaimana hubungan antara kondisi cuaca dan musim dengan jumlah pengguna sepeda? Kondisi cuaca dan musim seperti apa yang menyebabkan jumlah pengguna sepeda berada di titik tertinggi?
  
## Kebutuhan dan Instalasi

Proyek ini memerlukan pustaka-pustaka berikut untuk berjalan dengan baik:

- Matplotlib 3.8.3
- NumPy 1.26.4
- Pandas 2.2.0
- Seaborn 0.13.2
- Streamlit 1.31.1
