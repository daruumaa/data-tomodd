Jadi untuk input HYpodd --> ambil dari raw data
nah disitu ada 2 tipe file:
- Untuk range 110 - 113: 2012-2017_5AB.pha
- Unutk range 110 - 114: 2012-2017_110-14_filtered_5AB.pha
baru dimasukin ke hypodd

*error terakhir:
no clustering performed.
Reading data ...   Sun Dec 24 04:03:05 2023
events =  1774
stations < maxdist =     42
 MAXDATA=              1000000
STOP >>> Increase MAXDATA in hypoDD.inc.

ini kemungkinan datanya kegedean jadi harus ditambahin limitnya tp gw udh coba ubanh hypoDD.inc tp gabisa

terus nilai MOD gw ambil dari jurnal dengan nilai 
Depth	Vp
-200	4.3
-2	4.66
0	4.9
10	6.85
20	7.09
30	7.73
40	7.73
50	7.74
60	7.74
70	7.74
80	7.8
90	7.92
100	8.04
110	8.07
120	8.1
130	8.12
140	8.15
150	8.17
160	8.2
170	8.22
240	8.85
1000	10

itu udh di proses semua di codingnya ada di event.ipnyb
nilai parameterisasinya 1.754
<img width="376" alt="image" src="https://github.com/daruumaa/data-tomodd/assets/88280598/90a5e429-40f9-481f-8ab7-0df188d9e799">

