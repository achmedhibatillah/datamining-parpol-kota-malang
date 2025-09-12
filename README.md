# DATA MINING INSTAGRAM PARTAI POLITIK
### PARTAI DI KOTA MALANG
Data kami meliputi beberapa informasi penting soal postingan yang dimiliki oleh akun-akun media sosial Instagram empat partai politik di Kota Malang. Keempat partai tersebut antara lain:
1. Partai Kebangkitan Bangsa (PKB) dengan username @pkb_mlg
2. Partai Solidaritas Indonesia (PSI) dengan username @psimalangofficial
3. Partai Gerakan Rakyat Indonesia (Gerindra) dengan username @dpcgerindrakotamalang
4. Partai Demokrasi Indonesia Perjuangan (PDIP) dengan username @dpcpdiperjuangankotamalang

Kami mengolah data menggunakan kode python bernama `analytics/analytic.py` untuk meng-konvert data `JSON` menjadi `XLSX` (berada di direktori analytics). Data media sosial yang berupa `JSON` kami peroleh melalui tools _Apify_. Output berada di dalam `analisis_konten.xlsx`.

Saya membuat proyek ini bersifat _open source_. Anda dapat menggunakan program kami untuk penelitian Anda jika diperlukan.

Berikut proses penggunaan program ini:

1. Instalasi program
```
git clone https://github.com/achmedhibatillah/datamining-parpol-kota-malang
```
2. Menuju direktori program
```
cd datamining-parpol-kota-malang
```
3. Instalasi requirements
```
pip install requirements.txt
```
4. Aktivasi environtment
```
source bin/activate
```
5. Modifikasi program (jika perlu, ubah `JSON` untuk penyesuaian akun media sosial dan isi variabel `files` di `analytics/analytic.py` sesuai kebutuhan)
6. Jalankan program `python`
```
python analytics/anaytic.py
```