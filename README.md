# customer-segmentation

Tujuan proyek ini adalah mensegmentasikan pelanggan berdasarkan pendapatan tahunan (annual income) dan skor pembeluan (score)

Metode penelitian yang digunakan adalah CRISP DM yaitu _business understanding, data understanding, data preparation, modelling, evaluation_. 
Penelitian ini menerapkan algoritma KMeans Clustering. Model data di evaluasi dengan menggunakan Elbow method dan Silhouette Analysis. 
Proses klaster yang dilakukan dengan menggunakan K-Means menghasilkan sebuah informasi gambaran karakteristik pelanggan yang telah terkelompok dan menghasilkan lima klaster pelanggan berdasarkan dua atribut yaitu pendapatan tahunan dan skor pembelian.

Bedasarkan hasil evaluasi dengan menggunkan Elbow Method dan Silhouetter Analysis, pengklasteran terbaik adalah berjumlah 5 klaster, dengan karakteristik pelanggan sebagai berikut:
Klaster 0 adalah pelanggan dengan skor pembelian menengah dan pendapatan menengah. Pelanggan ini diberi label Golden Customer* karena pelanggan ini berada dalam posisi stabil dan terdiri pelanggan dengan jumlah besar.
Klaster 1 adalah pelanggan dengan skor pembelian tinggi dan pendapatan tahunan rendah. Pelanggan ini diberi label Growable Customer*. Pelanggan ini merupakan pelanggan yang memberikan keuntungan bagi perusahaan, namun beresiko tidak stabil karena pendapatan tergolong rendah.
Klaster 2 adalah pelanggan dengan skor pembelian tinggi dan pendapatan tahunan tinggi. Pelanggan ini diberi label Valuable Customer* karena merupakan pelanggan yang memberikan  keuntungan terbesar bagi perusahaan
Klaster 3 adalah pelanggan dengan skor pembelian rendah dan pendapatan tahunan rendah. Pelanggan ini diberi label Typical Customer* dilihat dari karakterisktik bahwa pelanggan melakukan transaksi sesuai dengan pendapatan tahunan mereka.
Klaster 4 adalah pelanggan dengan skor pembelian rendah dan pendapatan tahunan tinggi. Pelanggan ini diberi label Dormant Customer*

*)sebutan segmen pelanggan berdasarkan pendapat penulis
