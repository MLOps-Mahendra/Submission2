# Submission 1: Machine Learning Pipeline - Heart Disease Prediction
Nama: Mahendra Dwi Karunia Madjid

Username dicoding: mahendradwikm

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Heart Disease. Exploratory data analysis.](https://www.kaggle.com/code/georgyzubkov/heart-disease-exploratory-data-analysis/input) |
| Masalah | Penyakit jantung adalah sekelompok penyakit yang terkait dengan gangguan pada sistem kardiovaskular, yang ditandai oleh gangguan fungsi normal jantung. Penyakit ini dapat disebabkan oleh kerusakan pada epicardium, perikardium, miokardium, endokardium, alat katup jantung, dan pembuluh darah jantung. |
| Solusi machine learning | Teknologi machine learning menawarkan solusi untuk mendeteksi dini potensi penyakit jantung sebelum mencapai tahap yang serius. Dengan sistem prediksi yang menggunakan parameter seperti riwayat penyakit dan aktivitas harian, diharapkan dapat mempermudah deteksi dini oleh tenaga medis dan masyarakat umum. |
| Metode pengolahan | Pada proyek ini, dData kategorikal diolah menggunakan one-hot encoding, sementara data numerik dinormalisasi untuk memastikan konsistensi dalam analisis. |
| Arsitektur model | Model prediksi penyakit jantung ini melibatkan preprocessing data dengan one-hot encoding untuk data kategorikal dan normalisasi untuk data numerik. Model ini kemudian dilatih menggunakan algoritma machine learning untuk memprediksi adanya potensi penyakit jantung berdasarkan data yang diberikan. |
| Metrik evaluasi | Evaluasi model menggunakan metrik seperti akurasi, presisi, recall, dan F1-score untuk mengukur kualitas prediksi. Akurasi mengindikasikan seberapa akurat model dalam memprediksi, sedangkan presisi, recall, dan F1-score memberikan gambaran tentang ketepatan dan kelengkapan prediksi. |
| Performa model | PPerforma model dievaluasi berdasarkan metrik akurasi, presisi, recall, dan F1-score. Evaluasi menunjukkan model ini memiliki akurasi tinggi dengan presisi dan recall yang seimbang, menandakan kemampuannya dalam mendeteksi penyakit jantung secara efektif dan mengurangi kesalahan prediksi. |
| Opsi Deployment | Proses model deployment memanfaatkan aplikasi Railway. |
| Web App | https://mahendradwikm-pipeline-production.up.railway.app/v1/models/heart-disease-model/metadata |
| Monitoring | Monitoring dari hasil model serving menggunakan Prometheus |
