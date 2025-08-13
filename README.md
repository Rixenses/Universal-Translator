# Universal Translator

Translator otomatis multi-format (XML, TXT, JSON, PDF, DOCX, XLSX, PPTX) yang mempertahankan format asli dan tidak memerlukan API key.

Automatic multi-format translator (XML, TXT, JSON, PDF, DOCX, XLSX, PPTX) that preserves the original format and requires no API key.

---

## Fitur / Features
- *Multi-format*: .xml, .txt, .json, .pdf, .docx, .xlsx, .pptx
- *Preserve Formatting*: Format asli tetap terjaga  
- *Gratis*: Menggunakan googletrans sehingga tidak butuh API Key  
- *Backup Otomatis*: Setiap file yang diterjemahkan dibuat salinannya terlebih dahulu  
- *Batch Translation*: Mengurangi risiko rate limit Google Translate  

---

## Instalasi / Installation
```bash
pip install googletrans==4.0.0-rc1
pip install PyMuPDF python-docx openpyxl python-pptx
```

## Cara Penggunaan / Usage
```bash
python UniversalTranslator.py --patch "PATH_FILE_OR_FOLDER" --lang "LANG_CODE"
```
Contoh / Example
```bash
python UniversalTranslator.py --patch "C:\Users\User\Documents" --lang "id"
python UniversalTranslator.py --patch "C:\Users\User\Documents" --lang "en"
```

---

## Catatan / Notes

  (ID)
- PDF translation akan menimpa teks lama, jadi layout dapat berubah
- Sangat disarankan untuk membuat backup sebelum menjalankan skrip ini di folder besar
- googletrans kadang eror kalau koneksi ke Google diblokir
- googletrans itu library Python open source (MIT License), jadi bebas digunakan untuk pribadi maupun proyek "open source", asal kamu paham ada banyak kemungkinan untuk eror karena ini bukan API resmi Google Translate.
- Format file seperti XML, TXT, JSON, PDF, DOCS, XLSX, PPTX bukanlah hal uang dilarang untuk diproses sendiri, apalagi kalau itu konten pribadi atau konten lain yang diizinkan.
- DILARANG MENJUAL & MENGKLAIM HASIL TERJEMAHAN TANPA IZIN DARI PEMILIK ASLI

  (EN)
- PDF translation will overwrite the old text, so the layout may change.
- It is highly recommended to make a backup before running this script in a large folder.
- googletrans sometimes errors if the connection to Google is blocked.
- googletrans is an open-source Python library (MIT License), so it is free to use for personal or “open source” projects, as long as you understand there is a high chance of errors because this is not an official Google Translate API.
- File formats such as XML, TXT, JSON, PDF, DOCS, XLSX, PPTX are not prohibited from being processed personally, especially if they contain personal content or other permitted content.
- SELLING & CLAIMING TRANSLATION RESULTS WITHOUT PERMISSION FROM THE ORIGINAL OWNER IS PROHIBITED.

---

## Legal & License Disclaimer

(ID)
Proyek ini dibuat *hanya untuk penggunaan pribadi dan non-komersial*.  
Segala penggunaan alat ini untuk memproses materi berhak cipta harus mematuhi syarat pemegang hak cipta asli.  
Pembuat skrip *tidak bertanggung jawab* atas penyalahgunaan atau konsekuensi hukum yang timbul dari penggunaannya.

(EN)
This project is intended *for personal and non-commercial use only*.  
Any use of this tool to process copyrighted materials must comply with the original copyright holder's terms.  
The author of this script is *not responsible* for any misuse or legal consequences arising from its use.

---
