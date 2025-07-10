# Kode_ITBackburner
Usaha Mikro, Kecil, dan Menengah (UMKM) di Indonesia sering menghadapi kesulitan dalam mengelola lonjakan permintaan pelanggan akibat keterbatasan sumber daya manusia, sehingga kualitas layanan menurun dan risiko kehilangan pelanggan meningkat, yang menunjukkan perlunya solusi berbasis teknologi untuk otomatisasi pengambilan keputusan. Penelitian ini menggunakan pendekatan regresi berbasis machine learning untuk memprioritaskan pelanggan, dengan membandingkan performa tiga metode yaitu Random Forest (RF), eXtreme Gradient Boosting (XGBoost), dan Light Gradient Boosting Machine (LightGBM), menggunakan data uji sintetik untuk mensimulasikan perilaku pelanggan UMKM. Evaluasi pada penelitian ini menggunakan empat metrik utama, yaitu Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), dan koefisien determinasi (R²). Hasil pengujian menunjukkan bahwa LightGBM memperoleh hasil terbaik dengan MAE sebesar 0.4804, MSE sebesar 0.3886, RMSE sebesar 0.6233, dan R² sebesar 0.9983. Penelitian ini memberikan kontribusi dalam pengembangan sistem manajemen pelanggan berbasis Artificial Intelligence (AI) yang mampu mendukung efisiensi layanan dan meningkatkan loyalitas pelanggan UMKM melalui penerapan sistem Customer Relationship Management (CRM) secara otomatis.

| Model         | MAE    | MSE    | RMSE   | R²     |
|---------------|--------|--------|--------|--------|
| Random Forest | 1.7740 | 4.9595 | 2.1081 | 0.9781 |
| XGBoost       | 0.8049 | 1.7120 | 1.2111 | 0.9935 |
| LightGBM      | 0.5071 | 0.4500 | 0.6708 | 0.9980 |
