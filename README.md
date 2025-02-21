**Latar Belakang**

Dalam dunia asuransi, kemampuan untuk memprediksi klaim dengan akurat sangat penting untuk meminimalisir risiko dan mempertahankan keuntungan perusahaan. Proses klaim yang cepat dan efisien menjadi kunci dalam meningkatkan kepuasan pelanggan sekaligus menjaga keberhasilan operasional bisnis. Namun, penanganan klaim pelanggan memerlukan evaluasi berbagai aspek dan pengambilan keputusan yang tepat, menjadikannya proses yang kompleks. Tantangan yang sering dihadapi perusahaan asuransi meliputi pengelolaan jumlah klaim, mendeteksi klaim yang bersifat fraud, serta memastikan klaim dapat diselesaikan dengan adil dan tepat waktu.

Oleh karena itu, penerapan teknologi machine learning dapat memberikan manfaat besar dalam meningkatkan akurasi dan efisiensi pengelolaan klaim. Dengan membangun sistem prediksi status klaim yang andal, perusahaan asuransi dapat mempercepat proses operasional, memperbaiki pengalaman pelanggan, dan mengoptimalkan distribusi sumber daya yang dimiliki.

**Tujuan**

Proyek ini bertujuan untuk membangun model prediksi yang mampu menentukan status klaim asuransi pelanggan secara akurat. Model ini dirancang untuk memanfaatkan data historis dengan mengintegrasikan informasi penting tentang pelanggan, rincian klaim, serta faktor-faktor kontekstual lainnya, sehingga dapat menghasilkan keputusan yang lebih presisi terkait klaim, baik itu disetujui maupun ditolak.

Dengan mengembangkan sistem berbasis machine learning, perusahaan berharap dapat mempercepat dan meningkatkan akurasi dalam pemrosesan klaim. Pendekatan ini tidak hanya akan mengurangi potensi kesalahan dalam pengambilan keputusan, tetapi juga mempersingkat waktu tunggu pelanggan secara signifikan.

Selain itu, proyek ini juga bertujuan untuk menganalisis hubungan antar fitur dalam dataset guna mengidentifikasi variabel-variabel yang berpengaruh besar terhadap status klaim, sehingga dapat memberikan wawasan yang lebih mendalam dalam proses pengelolaan klaim.

**Pendekatan Analisis**

Salah satu tantangan yang mungkin dihadapi dalam pengembangan model machine learning adalah terjadinya kesalahan prediksi, yaitu Type Error 1 dan Type Error 2.

1. Type Error 1 (False Positive): Kesalahan ini terjadi ketika model secara keliru mengidentifikasi klaim sebagai disetujui (positif), padahal sebenarnya klaim tersebut harus ditolak (negatif). Akibatnya, perusahaan dapat mengalami kerugian finansial karena klaim yang tidak valid tetap diproses.
2. Type Error 2 (False Negative): Sebaliknya, kesalahan ini terjadi ketika model memprediksi klaim sebagai ditolak (negatif), padahal klaim tersebut sebenarnya layak untuk disetujui (positif). Hal ini berisiko menyebabkan ketidakpuasan pelanggan dan potensi masalah hukum akibat penolakan klaim yang tidak semestinya.

Untuk memastikan evaluasi yang menyeluruh terhadap kinerja model, digunakan metrik seperti ROC (Receiver Operating Characteristic) dan AUC (Area Under the Curve). Kedua metrik ini membantu mengukur kemampuan model dalam menangani data yang tidak seimbang, sekaligus memberikan gambaran yang lebih lengkap tentang trade-off antara kesalahan Type Error 1 dan Type Error 2. Dengan pendekatan ini, perusahaan dapat membuat keputusan yang lebih akurat terkait persetujuan atau penolakan klaim, sehingga mendukung efisiensi operasional dan kepuasan pelanggan.

https://pengumpulancapstone-3-x4s6wkys9jb4bpaaq4ripc.streamlit.app/
