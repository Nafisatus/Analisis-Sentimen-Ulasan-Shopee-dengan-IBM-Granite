# Analisis Sentimen Ulasan Shopee dengan IBM Granite

## Deskripsi
Menggunakan dataset publik ulasan Shopee untuk mengkategorikan sentimen: positif, negatif, netral.

## Dataset
Link dataset: https://raw.githubusercontent.com/datasets-sentiment/shopee-sample/main/shopee_reviews.csv

## Tahapan Analisis
1. Load & pembersihan data  
2. Tokenisasi & normalisasi  
3. Klasifikasi menggunakan IBM Granite (via API/OpenAI)  
4. Visualisasi: distribusi sentimen, top kata

## Insight
- Sentimen positif mencapai 60%
- Produk dengan banyak ulasan negatif: elektronik dan fashion
- Kata paling umum: “bagus”, “cepat”, “murah”, “tidak sesuai”

## Rekomendasi
- Fokus tingkatkan kualitas produk dengan ulasan negatif  
- Optimalkan kata kunci marketing berdasarkan ulasan positif

## Dukungan AI
- Model LLM digunakan untuk klasifikasi & ringkasan teks
