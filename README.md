# World Happiness Report 2016

## Overview
Kebahagiaan adalah kondisi emosional yang dicirikan oleh perasaan senang, kepuasan, dan kepuasan diri. Meskipun ada banyak definisi kebahagiaan, itu sering dianggap sebagai sesuatu yang melibatkan perasaan positif dan kepuasan dalam kehidupan.

Laporan Kebahagiaan Dunia adalah studi penting tentang keadaan kebahagiaan di seluruh dunia. Laporan ini memberikan peringkat kepada 149 negara berdasarkan tingkat kebahagiaan yang dialami oleh penduduknya. Peringkat ini didasarkan pada sejumlah faktor termasuk pertumbuhan ekonomi, dukungan sosial, harapan hidup, kebebasan untuk membuat pilihan hidup, kedermawanan, dan persepsi korupsi. Laporan ini diterbitkan setiap tahun oleh Perserikatan Bangsa-Bangsa.

Dalam proyek analisis ini, kami akan mengeksplorasi dataset Laporan Kebahagiaan Dunia 201 dengan menggunakan library Python untuk ilmu data seperti Pandas, Matplotlib, dan Seaborn, dengan tujuan memvisualisasikan data melalui plot dan grafik guna membantu pemahaman data dan memberikan wawasan yang lebih mendalam tentang faktor-faktor yang memengaruhi kebahagiaan secara global. Dataset ini mencakup skor kebahagiaan dan berbagai indikator sosio-ekonomi untuk negara-negara di seluruh dunia.
## Descriptive Analysis
### Dataset
#### Data Preparation adn Exploration
Dataset World Happiness di tahun 2016. Data ini terdiri dari 157 dan 13 kolom
Skor Kebahagiaan dijelaskan oleh beberapa faktor berikut:
| Variabel | Penjelasan |
| ------ | ------ |
| Country | Daftar nama negara yang terdapat dalam dataset |
| Region | Wilayah di mana suatu negara berada |
| Happiness Rank | Peringkat kebahagiaan suatu negara |
| Happiness Score | Nilai atau skor yang menunjukkan tingkat kebahagiaan suatu negara |
| Lower Confidence Interval | Interval keyakinan lebih rendah dari skor kebahagiaan| 
| Upper Confidence Interval | Interval keyakinan atas dari skor kebahagiaan |
| GDP per capita | Nilai ekonomi suatu negara per individu |
| Healthy Life Expectancy | Angka harapan hidup sehat |
| Family | Sejauh mana keluarga berkontribusi terhadap perhitungan skor kebahagiaan |
| Freedom | kebebasan |
| Trust (Government Corruption) | persepsi korupsi pemerintah terhadap perhitungan skor kebahagiaan |
| Generosity | Sejauh mana kedermawanan berkontribusi terhadap perhitungan skor kebahagiaan |
| Dystopia Residual | nilai yang digunakan dalam model untuk mengukur tingkat ketidakberdayaan atau ketidaksempurnaan di luar faktor-faktor yang diukur dalam survei kebahagiaan |
## Insight
1. Happiness Score dipengaruhi hubungan yang kuat oleh faktor Economy(GDP per Capita), Health (Life Expetancy) dan Family
2. Negara-negara teratas dalam Happiness Score terutama terletak di wilayah Western Europe, sementara negara-negara di Sub-Saharan Africa memiliki Happiness Score yang lebih rendah.
3. Berdasarkan data World Happiness 2016, negara yang paling banyak berada di wilayah Sub-Saharan Africa, tetapi wilayah tersebut memiliki skor kebahagiaan yang rendah. Kemungkinan rendahnya skor kebahagiaan di wilayah Sub-Saharan Africa dikarenakan :
    ###1).  Tingkat penyakit yang tinggi, dikarenakan akses terbatas terhadap layanan yang berkualitas dan infrastruktur kesehatan yang buruk dapat menyebabkan peningkatan penyakit dan kematian yang berdampak negatif pada kesejahteraan masyarakat.
    ###2). Cenderung memiliki ekonomi yang lemah dengan tingkat penghasilan per kapita yang rendah dan tingkat pengangguran yang tinggi sehingga ekonomi yang lemah dapat menyebabkan ketidakstabilan sosial dan ekonomi, meningkatkan ketidakpuasaan, dan mengurangi tingkat kebahagiaan masyarakat
    ###3). Ketidakstabilan politik, konflik bersenjata, dan gangguan keamanan. Ketidakpastian politik dapat membatasi kebebasan individu dalam menjalani kehidupan sehari-hari dan merasa aman.

Kesimpulannya, faktor-faktor seperti kondisi ekonomi, keluarga, kesehatan, kebebasan, dan kepercayaan terhadap pemerintah merupakan beberapa faktor kunci yang berkontribusi pada tingkat kebahagiaan suatu negara.
