# SC
Pengelolaan data System Completion untuk project JTB, Indonesia 2018-2022
Berisi cource code untuk pengelolaan spreadsheet dari team, dari kondisi semula terfragmentasi untuk kemudian di olah, diambil informasi ayng diperlukan, disaring informasi yang redundant, untuk kemudian di sambung2kan dan di integrasikan dalam 1 tabel yg ringan di load dalam spreadsheet.

Spreadsheet yang dikelola
1. Data CMS : Checksheet CC/PC/COMM, ITR, PunchList, Certificate
2. SC18 : jumlah subsystem, commisisonable/tidak, nama system Owner
3. SC17 : Status transmital document ke client
4. Data loop : untuk identifikasi posisi Loop instrument di konstruksi/syscom/client

Display Tool
- dengan google sheet, menggunakan library standard gspread.

Ide pengembangan : 
- Membuat alur tampilan akhir yg lebih intuitif, sehingga persepsi tim sama untuk remaining work dan target
- Dihubungkan dengan tabel spreadhset lain dari disiplin lain , motor solorun/logistik/precom/finding QC/Commissioning/operational/vendor serviceman/spare part/ finding dls yg masih trafragment
- Pembuatan system dengan alur flow blok seperti dalam PID process
- Mesin pengolah punchlist, untuk pembuatan cluster jenis punchlist dengan labelling material/engineering/tagname/operationa/dst
- Memanfaatkan feature matplotlib/seaborn untuk visualisasi workfront dalam bentuk heatmap/scatterplot/barchart/dll
- Membuat mesin penghitung sscore prioritas pekerjaan
- silahkan ditambahkan
- menambahkan feature web scrapping untuk ambil data dari CMS secara automatic
- 
