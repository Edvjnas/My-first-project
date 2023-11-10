# My-first-project  
Sistemos parametrai:  
CPU Intel(R) Core(TM) i5-1035G1 CPU @ 1.00GHz   1.19 GHz  
Ram 8 gb  
SSD 256gb  

v0.3 test (list konteineris):  
1000 irasu testo laikas: 0.0156278  
1000 irasu testo laikas: 0.0156341  
1000 irasu testo laikas: 0.0156246  
vidurkis: 0.0156288  
  
10000 irasu testo laikas: 0.209301  
10000 irasu testo laikas: 0.234352  
10000 irasu testo laikas: 0.171854  
vidurkis: 0.205169  
  
100000 irasu testo laikas: 1.61869  
100000 irasu testo laikas: 1.57801  
100000 irasu testo laikas: 1.49981  
vidurkis: 1.56550  
  
1000000 irasu testo laikas: 14.1548  
1000000 irasu testo laikas: 14.0298  
1000000 irasu testo laikas: 14.0958  
vidurkis: 14.0935  

10000000 irasu testo laikas: 260.989  
10000000 irasu testo laikas: 268.935  
10000000 irasu testo laikas: 266.758  
vidurkis: 265.561  
(rūšiavimas į dvi grupes užtruko labai ilgai ~160s)  
  
v0.2 test (vector konteineris): 
  
1000 irasu testo laikas: 0.0139497  
1000 irasu testo laikas: 0.0131364  
1000 irasu testo laikas: 0.0129571  
vidurkis: 0.013347733  
  
10000 irasu testo laikas: 0.131992  
10000 irasu testo laikas: 0.122589  
10000 irasu testo laikas: 0.119868  
vidurkis: 0.124816333  
  
100000 irasu testo laikas: 1.14821  
100000 irasu testo laikas: 1.28602  
100000 irasu testo laikas: 1.17355  
vidurkis: 1.2025933  
  
1000000 irasu testo laikas: 13.2721  
1000000 irasu testo laikas: 12.109  
1000000 irasu testo laikas: 15.5167  
vidurkis: 13.6326  
  
10000000 irasu testo laikas: 162.156  
10000000 irasu testo laikas: 126.875  
10000000 irasu testo laikas: 123.647  
vidurkis: 137.55933  
 
| List                | Vector              | Studentu sk. (10 namu darbu)|
|---------------------|---------------------|---------------|
| 0.0156288  | 0.013347733| 1000          |
| 0.205169   | 0.124816333| 10000         |
| 1.56550    | 1.2025933  | 100000        |
| 14.0935    | 13.6326    | 1000000       |
| 265.561    | 137.55933  | 10000000      |

Išvados: Vector konteineris šiuo atveju veikia greičiau nei list konteineris. Rūšiavimas užtruko daug ilgiau su list konteineriu, nes list turi iteruoti per visą sąrašą, kad pasiektų indeksą, o vector konteineris - ne. 
