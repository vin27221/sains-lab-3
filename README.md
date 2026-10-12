# SainsLab — Streamlit

Aplikasi belajar sains interaktif berbasis Python dan Streamlit.

## Isi aplikasi
- Simulasi jatuh bebas dengan grafik
- Visualisasi orbit delapan planet
- Kalkulator rumus sains
- Eksperimen virtual ayunan sederhana
- Kuis sains dengan pembahasan

## Menjalankan di komputer (VS Code)

1. Ekstrak ZIP ini.
2. Buka folder `SainsLab-Streamlit` di VS Code.
3. Buka Terminal di VS Code.
4. Jalankan:

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Streamlit akan memberi alamat lokal, biasanya `http://localhost:8501`.

## Deploy ke Streamlit Community Cloud

1. Buat repository GitHub baru.
2. Upload **isi folder ini** ke root repository. Pastikan `app.py`, `science.py`, dan `requirements.txt` langsung terlihat saat membuka repository, bukan berada satu folder lagi di dalamnya.
3. Buka https://share.streamlit.io/ dan masuk dengan GitHub.
4. Pilih **Create app**, lalu pilih repository dan branch yang benar.
5. Isi **Main file path** dengan `app.py`.
6. Klik **Deploy**.

Jika repository sudah ada, unggah/ganti file `app.py`, `science.py`, dan `requirements.txt` di root repository. Lalu pastikan pengaturan aplikasi menunjuk ke `app.py`.

## Catatan
- Semua simulasi menggunakan model edukatif dan asumsi yang dijelaskan di aplikasi.
- `__pycache__` dan file `.pyc` sengaja tidak disertakan karena dibuat otomatis oleh Python dan tidak diperlukan untuk deployment.
