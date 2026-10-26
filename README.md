# Recap_PO — versi ringan

Upload SELURUH isi folder ini ke repo GitHub (timpa index.html lama):

- index.html
- libs/  (xlsx.full.min.js, fflate.min.js, pdf.worker.js, pdf.js)
- assets/ (logo.png)

Library di libs/ hanya diunduh saat fiturnya dipakai (upload/export Excel, baca PDF, ZIP).
ExcelJS & PapaParse tetap dari CDN cdnjs, juga hanya saat dipakai.
Catatan: baca PDF memakai modul ES, jadi harus dibuka lewat http(s) (GitHub Pages), bukan file://.
