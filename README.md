# Visualisasi IPM vs Pengeluaran Perkapita Provinsi di Indonesia
Merupakan visualisasi scatter plot sederhana dengan menggunakan library matplotlib. Visualisasi ini dibuat untuk mengetahui bagaimana hubungan antara Indeks Pembagunan Manusia (IPM) dengan Pengeluaran per Kapita provinsi di indonesia. 

## Teknologi yang digunakan
Penulisan kode dilakukan pada jupyter notebook dengan bahasa pemrogaman python. Serta menggunakan library matplotlib, pandas, dan numpy.

## Persiapan data
Data yang digunakan diperoleh dari :
* https://www.bps.go.id/indicator/12/1886/1/jumlah-penduduk-hasil-proyeksi-menurut-provinsi-dan-jenis-kelamin.html
* https://ipm.bps.go.id/data/nasional

## Pengolahan data
Sebelum dilakukan visualisai, data yang diperoleh perlu diolah terlebih dahulu meliputi :
* Menggabungkan kedua data dengan index berupa nama provinsi
* Melakukan verifikasi pada nilai data gabungan
* Mengisi nilai data yang kosong

## Visualisasi
Dari data yang diolah, bagian yang digunakan akan untuk visualisasi adalah IPM, Pengeluaran perkapita, dan populasi pada tahun 2018. Pengeluaran perkapita 2018 dan IPM 2018 akan digunakan sebagai nilai x dan y pada scatter plot. Kemudian untuk populasi 2018 digunakan sebagai ukuran untuk marker. Hasilnya seperti berikut,

![Scatter plot hasil visualisasi](https://github.com/negatively/Indonesia-IPMvsPengeluaran/blob/main/ipmVSpengeluaran2018.png)

## Kesimpulan
Dari hasil visualisasi tersebut dapat disimpulkan bahwa IPM dan pengeluaran perkapita memiliki korelasi positif. Dimana semakin tinggi Pengeluaran perkapita suatu provinsi, maka semakin tinggi juga nilai poin IPM provinsi tersebut. Karena banyak populasi juga digunakan dalam visualisasi ini, dapat diketahui bahwa semakin banyak jumlah populasi pada suatu provinsi belum tentu nilai IPM dan pengeluaran perkapita-nya semakin tinggi juga. Beda cerita lagi apabila jika dibandingkan dengan nilai tingkat kepadatan penduduk suatu provinsi.
