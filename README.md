# cara memakai sqlmap + burp suite

1.masukan url hasil droking pada burp suit dan jalankan intercept on

2.paste pada browser (setelah itu copy hasil dari intercept)

3.buka terminal lalu paste echo " hasil dari intercept " > filename.txt

4.jalakan sqlmap (sqlmap -r filename.txt) bisa custom --tamper=space2commet --level 1 --risk 1
