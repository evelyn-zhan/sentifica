# Sentifica 🧠

Sentifica merupakan sebuah _website_ yang dibuat sebagai hasil _project_ tugas mata kuliah Kecerdasan Artifisial. _Website_ ini dapat menganalisis sentimen dari teks yang dimasukkan.

#### Kelompok Bika Ambon Ci Suti

- Evelyn (231111684)
- Jesslyn Caroline (231111664)
- Nadia Narda (231111490)
- Sutiati (231112244)
- Elviola Mahayana (231110548)

#### Pembagian Tugas 📝

1. Frontend 💻
- Jesslyn Caroline: Mendesain dan membuat tampilan dari halaman awal _website_, serta mengintegrasikan sisi Frontend dengan Backend dengan _axios_.
- Sutiati: Membuat tampilan dari halaman kedua, yaitu halaman untuk meng-_input_ teks yang akan dianalisis.

2. Backend ⚙️
- Evelyn: Merancang API agar teks yang dikirim dari Frontend dapat diteruskan ke model untuk dianalisis.

3. Model 🤖
- Evelyn: Membuat model kecerdasan buatan dengan algoritma _Naive Bayes_ untuk memprediksi sentimen kalimat.
- Elviola Mahayana: Membantu dalam mengumpulkan _dataset_ serta membuat model dengan algoritma _Logistic Regression_.
- Nadia Narda: Membantu dalam mengumpulkan _dataset_.

#### Cara Menjalankan _Project_ Ini ▶️

Untuk melihat hasil dari _project_ ini, Anda dapat langsung mengunjungi [sentifica.vercel.app](sentifica.vercel.app)
**⚠️ Latest Update: Model service untuk _project_ ini sudah dimatikan sehingga hanya bisa dijalankan secara lokal dengan mengunduh repository ini.**

Untuk menjalankannya pada _localhost_, lakukan hal-hal berikut:

**Menjalankan sisi Frontend**
```
cd frontend
npm install
npm run dev
```

**Menjalankan sisi Backend**
```
cd backend

pip install pandas
pip install re
pip install scikit-learn
pip install joblib
pip install flask
pip install flask-cors

py app.py
```

#### Teknologi yang Digunakan ⚡
- Library / Framework yang digunakan pada sisi Frontend adalah ReactJS.
- Sedangkan untuk Backend, digunakan Framework Flask
- Untuk membangun model, digunakan library pandas, scikit-learn, dan joblib
