# fastfood-calorie-classifier
# Problem Statement

Tujuan dari proyek ini adalah mengklasifikasikan restoran berdasarkan informasi kandungan gizi dari menu makanannya.
Dataset berisi informasi menu makanan dari beberapa restoran cepat saji seperti McDonald's, Burger King, dsb, beserta data nutrisi seperti kalori, lemak, kolesterol, protein, dan kalsium.

Pertanyaan:
- Apakah mungkin menebak restoran asal sebuah makanan hanya dari nilai gizinya?
- Apa saja fitur (nutrisi) yang paling berpengaruh terhadap klasifikasi?

Proyek ini menggunakan algoritma Random Forest untuk mengklasifikasikan makanan cepat saji berdasarkan informasi gizi. Dataset mencakup kalori, lemak, kolesterol, protein, dll.

## Teknologi
- Python
- Scikit-Learn
- Pandas
- Seaborn

## Hasil
Akurasi: 85%  
Fitur paling penting: kalori, protein, total_fat

## Struktur
- notebook.ipynb
- menu.csv
- model_random_forest.pkl
