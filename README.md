# Klasifikasi Sentimen
Project ini merupakan implementasi sistem klasifikasi sentimen teks yang dibuat untuk memenuhi tugas Ujian Akhir Semester (UAS) pada mata kuliah Natural Language Processing.
## Identitas Mahasiswa
Nama: Alzabir Khalid 
Nim: 24146097

---

## Deskripsi Singkat
Sistem ini bertujuan untuk mengklasifikasikan komentar teks ke dalam tiga kategori sentimen, yaitu positif, netral, dan negatif. Algoritma yang digunakan adalah Multinomial Naive Bayes dari library scikit-learn.

---

## Penjelasan Sistem
Tahapan yang dilakukan dalam sistem ini meliputi:
1. Preprocessing teks, yang terdiri dari:
   - Case folding
   - Tokenizing
   - Stopword removal
   - Stemming Bahasa Indonesia
2. Transformasi teks menjadi data numerik menggunakan CountVectorizer
3. Pembagian dataset menjadi data latih dan data uji dengan rasio 80% : 20%
4. Pelatihan model menggunakan algoritma Multinomial Naive Bayes
5. Evaluasi model menggunakan classification report dan confusion matrix

---

## Output
Program akan menampilkan preprocessing teks dan hasil evaluasi berupa:
- Case folding
- Tokenizing
- Stopword removal
- Stemming Bahasa Indonesia
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Kesimpulan
Dengan menerapkan algoritma Multinomial Naive Bayes dan tahapan
preprocessing yang sesuai, sistem ini mampu melakukan klasifikasi
sentimen teks secara otomatis dengan baik.
