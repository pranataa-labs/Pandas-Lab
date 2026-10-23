# Pandas Lab — Data Wrangling, Cleaning & Analysis

**Tech Stack:** Python 3.10+, Pandas, NumPy, Jupyter Notebook.  
**Standards & Operating Workflow:** Terintegrasi penuh dengan [Workflow Master](.workflow/README.md).

---

## 1. Operating Discipline & Engineering Workflow
Semua pekerjaan analisis data dan coding pada repositori ini WAJIB mematuhi 9 tahapan alur kerja di `.workflow/workflows/00-engineering-workflow-ai-coding.md`:
1. **Triage:** Pahami tujuan eksplorasi data, identifikasi anomali, dan tentukan cakupan analisis.
2. **Discover:** Periksa dataset (`.csv`, `.xlsx`, `.sqlite`), tipe kolom, null values, dan memory usage.
3. **Design:** Rancang pipeline transformasi data (cleaning, aggregation, feature engineering).
4. **Plan:** Tentukan notebook/script yang akan dimodifikasi atau dieksekusi.
5. **Implement:** Tulis kode Pandas yang idiomatis, vektorisasi (hindari iterrows manual lambat), dan reproducible.
6. **Verify:** Validasi bentuk data (`df.shape`), tipe data, tidak ada missing values tak terduga, dan konsistensi perhitungan.
7. **Review:** Evaluasi performa eksekusi dan kebersihan visualisasi grafik.
8. **Release:** Bersihkan cell output besar jika tidak diperlukan sebelum commit.
9. **Report:** Laporkan insight bisnis dan hasil temuan data secara transparan.

---

## 2. Aturan Khusus Data Analysis
- **Reproducibility:** Selalu gunakan random seed tetap jika melakukan sampling.
- **Data Integrity:** Jangan menimpa raw dataset asli tanpa backup/transformasi bertahap.
