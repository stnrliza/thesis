# Decision Support System Berbasis Machine Learning bagi Dokter Gigi dan Pasien pada Pemeriksaan Karies Sekunder
A repo dedicated for my thesis :D soon will be changed

## To do:

✅ 1. cari dataset (dari PKM)
*note: ini gabungan NILT sama engga, soalnya nyari NILT aja limited banget, digabung sama yang biasa tp grayscale, udah labelled dari anak FKG*

2. - training model (gambar aja, instance segmentation)
   - cari korelasi dataset gambar dengan model lain (tabular terutama) <-- bahan multimodal, sekalian memperkuat latar belakang dan rumusan masalah

3. link datasetnya (gimana yah blom kepikiran soalnya dataset yang ada itu cuman gambar doang tanpa info demografinya. ada alternatif lain kah biar tetap bisa multimodal?)

4. training semuanya (multimodal: gambar dan tabular/model lain)

### To do tambahan:
5. tambahin LLM/n8n (atau trending topics tp tetap relevan ga maksa, ada urgensinya)

6. bikin website untuk menghimpun semuanya (front end, back end, cloud, model prediction, otomatisasi, dll)

## KERANGKA LATAR BELAKANG
1.1.	Latar Belakang
Masalah nyata --> keterbatasan metode saat ini --> celah riset --> solusi yang diusulkan
1.	Konteks kesehatan gigi
   
   a.	Kesehatan gigi masih jadi isu dominan di kesehatan masyarakat
  	
   b.	Karies gigi penyakit mulut dominan (beserta pengertian)
   
   c.	Karies sekunder sering luput karena terjadi di restorasi
   
2.	Tantangan klinis karies sekunder
   
   a.	Karies sekunder sulit dideteksi secara visual (beserta pengertian)
   
   b.	Bergantung pada pengalaman dokter (leading ke misinterpretasi atau human error)
   
   c.	Interpretasi citra NILT tidak selalu trivial
   
3.	Keterbatasan pendekatan konvensional
   
   a.	Interpretasi manual rawan subjektif
   
   b.	Dokumentasi hasil pemeriksaan tidak selalu terstandarisasi
   
   c.	Pasien sering tidak memahami hasil pemeriksaan
   
4.	Potensi ML sebagai DSS
   
   a.	ML efektif untuk analisis citra medis
   
   b.	ML cocok digunakan sebagai DSS
   
   c.	DSS berupa laporan membantu dokter sebagai pendukung, membantu pasien untuk memahami interpretasi dan dokumentasi
   
5.	Celah riset
   
   a.	Sebagian besar penelitian hanya fokus pada akurasi deteksi
   
   b.	Skripsi ini dibuat untuk membahas tentang explainable DSS end-to-end: akurasi deteksi, dokumen terstruktur dan mudah dipahami pasien
