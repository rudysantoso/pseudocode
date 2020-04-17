algoritma
resultan gaya pada sebuah mobil yang memiliki massa benda 600 kg dan ketika didorong oleh tiga orang percepatannya adalah 2 m/s2# pseudocode
pseudocode
STORE "massa" WITH VALUE 600 
STORE "percepatan" WITH VALUE 2
SET "gaya" EQUAL TO "massa" TIMES "percepatan"
    DISPLAY "gaya"

algoritma
Jika tahun habis di bagi 4 dan tidak habis di bagi 100, atau
Jika tahun habis di bagi 4, habis di bagi 100 dan habis di bagi 400
pseudocode
STORE "year" WITH ANY VALUE
IF "year" MOD WITH 4 EQUAL TO 0 AND "year" MOD WITH 100 EQUAL TO 1 THEN 
    DISPLAY "tahun kabisat"
ELSE IF "year" MOD WITH 4 EQUAL TO 0 AND "year" MOD WITH 100 EQUAL TO 0 AND "year" MOD WITH 400 EQUAL TO 0 THEN
    DISPLAY "tahun kabisat"
ELSE
    DISPLAY "tidak tahun kabisat"

algoritma
Pakaian yang akan dicuci oleh Foxie sebanyak 20 dan akan dimasukkan ke mesin cuci. Mesin cuci akan dinyalakan jika semua pakaian Foxie sudah masuk ke mesin cuci.
pseudocode
STORE "maxPakaian" WITH VALUE 20 
STORE "pakaian" WITH VALUE 1
WHILE "pakaian" LOWER TO "maxPakaian" THEN
    DISPLAY "mesin cuci belum menyala"
END WHILE
    DISPLAY "mesin cuci menyala"

algoritma
Seorang guru akan memeriksa kuku siswa-siswinya yang sebanyak 40 orang dengan cara berkeliling kelas. 
Jika guru menemukan siswa/siswi yang memiliki kuku yang panjang maka guru akan menghukum siswa/siswi tersebut 
jika tidak guru akan memuji siswa/siswi tersebut
pseucode
STORE "maxSiswa" WITH VALUE 40
STORE "siswa" WITH VALUE 0
STORE "kukuSiswa" WITH VALUE "panjang" OR "pendek"
WHILE "siswa" LOWER TO 40
IF "kukuSiswa" EQUAL TO "panjang" THEN
    DISPLAY "guru marah"
ADD "siswa" WITH VALUE 1
ELSE IF "kukuSiswa" EQUAL TO "pendek" THEN
    DISPLAY "guru muji"
ADD "siswa" WITH VALUE 1
END WHILE



tugas 2
