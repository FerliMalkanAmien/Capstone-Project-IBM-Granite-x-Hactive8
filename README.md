Analisis dan Penyesuaian Model Bahasa Besar (LLM) untuk Klasifikasi Ulasan dan Ringkasan Transkrip
Proyek ini adalah studi kasus yang mendemonstrasikan bagaimana parameter model bahasa besar (LLM) dapat disesuaikan untuk mengoptimalkan kinerjanya pada tugas-tugas Pemrosesan Bahasa Alami (NLP) spesifik. Menggunakan pustaka LangChain dan model ibm-granite/granite-3.3-8b-instruct dari Replicate, proyek ini membandingkan hasil dari parameter default versus yang disesuaikan untuk dua skenario utama: klasifikasi ulasan pelanggan dan ringkasan transkrip rapat.
Deskripsi Proyek
Notebook ini mengeksplorasi dua aplikasi praktis LLM dalam konteks bisnis:
Klasifikasi Sentimen dan Area Fokus: Menganalisis ulasan pengguna untuk mengklasifikasikan sentimennya (positif, negatif, atau campuran) dan mengidentifikasi area fokus seperti Performa, UI/UX, Dukungan Pelanggan, Harga, atau Fitur.
Ringkasan Transkrip: Meringkas transkrip rapat yang panjang untuk mengekstrak dan menyajikan informasi kunci secara terstruktur, termasuk keputusan utama, item tindakan, dan tenggat waktu.
Melalui penyesuaian parameter seperti top_k, top_p, max_tokens, dan repetition_penalty, proyek ini menunjukkan peningkatan signifikan dalam akurasi, keringkasan, dan relevansi keluaran model.
Prasyarat
Sebelum menjalankan notebook ini, Anda memerlukan:
Akun di Replicate.
Token API Replicate.
Instalasi
Instal pustaka Python yang diperlukan dengan menjalankan perintah berikut:
pip install langchain_community replicate


Penggunaan
Unggah atau buka notebook Analisis_dan_Penyesuaian_Model_Bahasa_Besar_(LLM)_untuk_Klasifikasi_Ulasan_dan_Ringkasan_Transkrip_Menggunakan_LangChain_dan_Replicate.ipynb di Google Colab.
Tambahkan token API Replicate Anda sebagai rahasia Colab dengan nama REPLICATE_API_TOKEN.
Jalankan setiap sel kode secara berurutan. Notebook akan secara otomatis menginstal dependensi, mengonfigurasi API, dan menjalankan eksperimen klasifikasi dan ringkasan.
Struktur Notebook
Setup: Instalasi dan impor pustaka, serta konfigurasi token API.
Klasifikasi Ulasan:
Pengujian dengan parameter default.
Penyesuaian parameter dan perbandingan keluaran.
Ringkasan Transkrip:
Pengujian dengan parameter default.
Penyesuaian parameter dan perbandingan keluaran.
Kesimpulan: Analisis hasil dan pentingnya penyesuaian parameter.
Hasil Utama
Klasifikasi: Parameter yang disesuaikan menghasilkan klasifikasi yang lebih terperinci dan bernuansa.
Ringkasan: Parameter yang disesuaikan menghasilkan ringkasan yang lebih ringkas dan terstruktur.
Proyek ini berfungsi sebagai panduan praktis untuk mengoptimalkan kinerja model LLM untuk tugas-tugas spesifik, menunjukkan bahwa pemahaman dan penyesuaian parameter sangat penting untuk mencapai hasil yang diinginkan.
