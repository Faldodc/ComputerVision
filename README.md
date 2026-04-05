# ComputerVision
Proyek ini bertujuan untuk menganalisis 10 citra batik motif Parang secara numerik menggunakan Python di Google Colab. Proses mencakup preprocessing, ekstraksi fitur tekstur, visualisasi, clustering, PCA, dan identifikasi fitur paling berpengaruh. Hasil analisis dapat digunakan untuk memahami pola motif batik secara sistematis, serta sebagai dasar klasifikasi atau studi lanjutan dalam computer vision dan data science.

Metode
GLCM (Gray Level Co-occurrence Matrix): Mendeteksi hubungan antar piksel untuk memperoleh fitur tekstur seperti contrast, homogeneity, energy, correlation, dan ASM.
Statistik Orde Pertama: Menganalisis distribusi intensitas piksel secara global, mencakup mean, standar deviasi, variance, skewness, kurtosis, dan entropy.
LBP (Local Binary Pattern): Mengidentifikasi pola lokal dengan membandingkan piksel pusat dengan tetangganya, fitur yang diambil meliputi mean, standar deviasi, dan energy.
Visualisasi: Histogram, heatmap, dan PCA untuk melihat distribusi, korelasi, dan pengelompokan data.
Clustering: Mengelompokkan citra berdasarkan kemiripan fitur tanpa label.
Feature Importance: Menentukan fitur tekstur yang paling berpengaruh pada motif batik.
