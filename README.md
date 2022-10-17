# Tentang projek kredit scoring
Kredit scoring analisis merupakan salah satu model data science yang banyak digunakan dalam dunia keuangan, khususnya bank dan asuransi.
Dengan model yang dibuat, harapannya mampu memberikan prediksi kepada calon peminjam apakah nantinya mereka akan membayar lunas pinjaman atau gagal bayar (defaulter).
Tentunya, dengan adanya model seperti ini, pihak pemberi pinjaman bisa menghindari calon peminjam yang diprediksi gagal bayar yang akan berdampak ke lebih sehatnya keuangan perusahaan.

#Model
Model yang digunakan ialah Random Forest, XGBoost dan Ligth Gradient Boost. Didapatkan Light Gradient Boost(LGBM) bisa memprediksi dengan tingkat akurasi sebesar 72%. Disini digunakan score roc_auc dikarenakan target variabel yang imbalance. Menurut Deloitte, skor diatas 70% sudah bisa diterima dan diuji coba.

#Faktor yang memperanguhi model
Berdasarnya model LGBM, beberapa faktor yang mempengaruhi gagal tidaknya seseorang melakukan pemabayar atas pinjamannya yaitu besarnya bunga (int_rate), besarnya income peminjam (annual_inc), rasio total pembayaran kredit per total utang(dti), revo_util, & revo_bil.


