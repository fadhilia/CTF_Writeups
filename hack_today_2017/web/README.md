# Hack Today 2017: Time is Money

**Category:** Web
**Points:** 65

## Write-up

- Tidak terdapat clue apapun pada misi ini sehingga kami mencoba untuk mengecek respon status kode yang dikirim.
- Karena kami sudah tahu bahwa flag berawalan strings “HackToday{” dan mendapat respon status kode 302, sedangkan apabila mengirimkan strings acak seperti “asd” respon yang didapat adalah 403, yang mengartikan bahwa strings awal yang kami kirim adalah valid.
- Langkah selanjutnya kami coba bruteforce tiap karakter.
- Didapatlah flag : `HackToday{long_l000ng_flag_is_panjaaa44ng_panjaaanggg_b3ndeeeraaa}`.
