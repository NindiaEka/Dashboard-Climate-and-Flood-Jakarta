#  Flood Analytics for Farmers

## Repository Outline
1. README.md - Penjelasan gambaran umum project
2. P0M1_Nindia-Ekasuci.ipynb - Notebook yang berisi pengolahan data dengan python
3. P0M1_Nindia-Ekasuci_dataset.csv - File csv dari hasil export di VS code
4. P0M1_Nindia-Ekasuci_dataset.xls - File excel dari hasil csv untuk import ke tableau
5. Data_raw.csv - File csv yang diambil dari website kaggle
6. Milestone1.twbx - File tableau yang berisi dashboard hasil visualisasi, analisa deskriptif dan inferensial
7. Peta_DKIJakarta.shp - File shapefile untuk input peta ke dalam tableau
8. GeoJKT.geojson - File geojson untuk input peta ke dalam python (membuat choropleth)


## Problem Background
Cuaca ekstrem dan banjir merupakan tantangan besar bagi petani, terutama di wilayah Jakarta dan sekitarnya. Banjir yang tidak terprediksi dapat merusak tanaman, menunda masa tanam, hingga menyebabkan gagal panen. Informasi terkait pola cuaca dan musim banjir masih jarang diakses secara sistematis oleh petani.
Analisis data cuaca dan kejadian banjir selama lima tahun terakhir diharapkan dapat membantu petani dalam mengambil keputusan yang lebih tepat terkait waktu tanam, pemupukan, dan panen, serta sebagai dasar mitigasi risiko gagal panen akibat banjir.


## Project Output
Output project ini adalah dashboard yang menampilkan data curah hujan dan banjir yang nantinya akan digunakan sebagai pengambilan keputusan  yang lebih tepat terkait waktu tanam dan mengurasi resiko gagal panen akibat banjir. Berikut link dashboard nya https://public.tableau.com/app/profile/nindia.ekasuci.larasati/viz/P0M1_Nindia-Ekasuci/Dashboard1?publish=yes.

## Data
Dataset bisa diakses pada link berikut :
https://www.kaggle.com/datasets/christopherrichardc/climate-and-flood-jakarta/data
Jumlah kolom awal ada 6308 baris dengan 15 kolom. Ada beberapa missing value pada data ini, yaitu pada data curah hujan dan waktu lama penyinaran. Missing value tersebut diimputasi dengan nilai median dari masing - masing kolom. Alasan menginputasi data karena jika data di hapus maka ada informasi (nama stasiun) yang menghilang.

## Method
1. Data Cleaning : Menghapus data yang tidak lengkap dengan menggunakan imputasi nilai median pada curah hujan dan lama penyinaranserta  menyatukan informasi cuaca dan banjir.
2. Statistik Deskriptif : Menghitung rata-rata, sebaran, skewness, dan kurtosis untuk memahami pola cuaca.
3. Visualisasi Data: Menggunakan line chart, bar chart, boxplot, dan choropleth map untuk melihat tren dan pola geografis.
4. Statistik Inferensial: ANOVA untuk uji perbedaan suhu antar bulan
5. Uji t untuk membandingkan suhu saat banjir dan tidak
6. Chi-square & Cramer's V untuk hubungan wilayah dan banjir

## Stacks
Stack yang digunakan yaitu menggunakan bahasa pemrograman python, tools yang digunakan adalah QGIS untuk mengekstrak wilayah menjadi file shapefile dan tableau untuk membuat dashboard. Library yang digunakan adalah pandas, numpy, matplotlib.pyplot, geopandas, folium, seaborn.

## Reference
- [Referensi Dashboard](https://public.tableau.com/app/profile/tam.s.varga/viz/Superstore-Bento-Box/PerformanceOverview)
- [Referensi Dashboard](https://public.tableau.com/app/profile/faishal.kemal/viz/DashboardSuicideAnalysis/SuicideDataAnalysis)
- [Referensi Data](https://www.kaggle.com/datasets/christopherrichardc/climate-and-flood-jakarta/data)
- [Hasil_dashboard](https://public.tableau.com/app/profile/nindia.ekasuci.larasati/viz/P0M1_Nindia-Ekasuci/Dashboard1?publish=yes)


