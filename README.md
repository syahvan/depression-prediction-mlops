# Human Depression Prediction

<p align="center">
  <img src="https://d3uhejzrzvtlac.cloudfront.net/compro/articleContent/703d5bda-019c-4500-a2f4-d6d6e46aff92.jpg" />
</p>


| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Depression: Reddit Dataset](https://www.kaggle.com/datasets/infamouscoder/depression-reddit-cleaned) |
| Masalah | Depresi adalah gangguan kesehatan mental yang ditandai oleh perasaan sedih yang berkepanjangan, kehilangan minat atau kesenangan dalam aktivitas sehari-hari, serta perubahan dalam pola tidur, nafsu makan, dan energi. Kondisi ini dapat mengakibatkan penurunan kualitas hidup yang signifikan dan membutuhkan intervensi medis yang tepat. |
| Solusi machine learning | Terkadang, depresi sulit dilihat dari aktivitas sehari-hari seseorang. Oleh karena itu, dengan machine learning, kita dapat mendeteksi tanda-tanda depresi melalui pola aktivitas dan ketikan seseorang di media sosial. Aktivitas ini dapat mencerminkan interaksi sosial dan emosional seseorang yang menjadi indikator potensial untuk mendeteksi depresi secara dini. |
| Metode pengolahan | Pada proyek ini, dataset yang digunakan memiliki dua fitur utama, yaitu `text` dan `depression`. Data dibagi menjadi data training dan evaluasi dengan perbandingan 80:20, di mana fitur `text` diubah menjadi lowercase dan fitur `depression` diubah menjadi tipe data integer. Metode pengolahan data yang diterapkan melibatkan tokenisasi, di mana teks input diubah menjadi urutan angka untuk merepresentasikan teks tersebut agar dapat dipahami dengan mudah oleh model. |
| Arsitektur model | Model yang dikembangkan memanfaatkan TextVectorization sebagai lapisan untuk mengubah teks input menjadi representasi numerik, diikuti oleh lapisan Embedding yang mempelajari hubungan antar kata untuk mengidentifikasi sifat positif atau negatif dari kata-kata tersebut. Selanjutnya, model ini terdiri dari 2 hidden layer dan 1 output. |
| Metrik evaluasi | Metrik yang digunakan untuk mengevaluasi performa model dalam klasifikasi meliputi Binary Accuracy, True Positive, False Positive, True Negative, dan False Negative. Metrik-metrik ini digunakan untuk mengukur seberapa baik model dapat membedakan antara kelas positif dan negatif, serta untuk menilai keakuratan prediksi model secara keseluruhan |
| Performa model | Model yang dibuat menghasilkan performa yang cukup baik dalam memberikan prediksi depresi pada text yang diinputkan, dan dari pelatihan yang dilakukan model menghasilkan binary_accuracy dan val_binary_accuracy di sekitar 98% |
