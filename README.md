# Bandit  
**Bandit Level 0**  
ssh bandit0@bandit.labs.overthewire.org -p 2220  
bandit0  
  
  
**Bandit Level 0 → Level 1**  
ssh bandit0@bandit.labs.overthewire.org -p 2220  
cat readme  
boJ9jbbUNNfktd78OOpsqOltutMc3MY1  
  
  
**Bandit Level 1 → Level 2**  
ssh bandit1@bandit.labs.overthewire.org -p 2220  
cd /home/  
cat bandit1/-  
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9  
  
  
**Bandit Level 2 → Level 3**  
ssh bandit2@bandit.labs.overthewire.org -p 2220  
cd /home/  
cat bandit2/spaces\ in\ this\ filename  
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK  
  
  
**Bandit Level 3 → Level 4**  
ssh bandit3@bandit.labs.overthewire.org -p 2220  
ls -a  
cat inhere/.hidden  
pIwrPrtPN36QITSp3EQaw936yaFoFgAB  
  
  
**Bandit Level 4 → Level 5**  
ssh bandit4@bandit.labs.overthewire.org -p 2220  
file -m inhere/  
koReBOKuIDDepwhWk7jZC0RTdopnAYKh  
  
  
**Bandit Level 5 → Level 6**  
ssh bandit5@bandit.labs.overthewire.org -p 2220  
find inhere/ -type f -size 1033c  
cat [filepath]  
DXjZPULLxYr17uwoI01bNLQbtFemEgo7  
  
  
**Bandit Level 6 → Level 7**  
ssh bandit6@bandit.labs.overthewire.org -p 2220  
find / -type f -user bandit7 -group bandit6 -size 33c [-ls]  
cat 'filepath'  
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs  
  
  
**Bandit Level 7 → Level 8**  
ssh bandit7@bandit.labs.overthewire.org -p 2220  
grep -n millionth data.txt   
cvX2JJa4CFALtqS87jk27qwqGhBM9plV  
  
  
**Bandit Level 8 → Level 9**  
ssh bandit8@bandit.labs.overthewire.org -p 2220  
sort data.txt | uniq -u  
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR  
  
  
**Bandit Level 9 → Level 10**  
ssh bandit9@bandit.labs.overthewire.org -p 2220  
strings -a data.txt  
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk  
  
  
**Bandit Level 10 → Level 11**  
ssh bandit10@bandit.labs.overthewire.org -p 2220  
cat data.txt | base64 -d  
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR  
  
  
**Bandit Level 11 → Level 12**  
ssh bandit11@bandit.labs.overthewire.org -p 2220  
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'  
5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu  
  
  
**Bandit Level 12 → Level 13**  
ssh bandit12@bandit.labs.overthewire.org -p 2220  
mkdir /tmp/new_dir  
cp data.txt /tmp/new_dir  
cd /tmp/new_dir  
xxd -r data.txt > data  
file data  
mv data data.gz  
gzip -d data.gz  
file data  
mv data data.bz2  
bzip2 -d data.bz2  
file data  
mv data data.gz  
gzip -d data.gz  
file data  
mv data data.tar  
tar -xvf data.tar  
file data5.bin  
mv data5.bin data.tar  
tar -xvf data.tar  
file data6.bin  
mv data6.bin data.bz2  
bzip2 -d data.bz2  
file data  
mv data data.tar  
tar -xvf data.tar  
file data8.bin  
mv data8.bin data.gz  
gzip -d data.gz  
file data  
cat data  
8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL  
  
  
**Bandit Level 13 → Level 14**  
ssh bandit13@bandit.labs.overthewire.org -p 2220  
cat sshkey.private  
copy the KEY and save it to your PC with nano/vim  
close bandit13 connection  
chmod 600 KEY  
ssh -i KEY bandit14@bandit.labs.overthewire.org -p 2220  
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e  
  
  
**Bandit Level 14 → Level 15**  
ssh bandit14@bandit.labs.overthewire.org -p 2220  
cat /etc/bandit_pass/bandit14  
echo 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e | nc localhost 30000  
BfMYroe26WYalil77FoDi9qh59eK5xNr  
  
  
**Bandit Level 15 → Level 16**  
ssh bandit15@bandit.labs.overthewire.org -p 2220  
cat /etc/bandit_pass/bandit15 | openssl s_client -connect localhost:30001 -quiet  
cluFn7wTiGryunymYOu4RcffSxQluehd  
  
  
**Bandit Level 16 → Level 17**  
ssh bandit16@bandit.labs.overthewire.org -p 2220  
nmap localhost -p31000-32000 `OR you can use` nc -zv localhost 31000-32000 `result is the same`  
`with` echo test | nc -v localhost <'port'> `find the two SSL use ports 31790 and 31518 (they don't answer)`  
`get RSA_PRIVATE_KEY and save it to your PC`  
chmod 600 RSA_PRIVATE_KEY  
xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn  
  
  
**Bandit Level 17 → Level 18**  
ssh bandit17@bandit.labs.overthewire.org -p 2220  
diff passwords.new passwords.old   
kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd  
  
  
**Bandit Level 18 → Level 19**  
ssh -t bandit18@bandit.labs.overthewire.org -p 2220 /bin/sh  
ls  
cat readme   
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x  
  
  
**Bandit Level 19 → Level 20**  
ssh bandit19@bandit.labs.overthewire.org -p 2220  
./bandit20-do cat /etc/bandit_pass/bandit20  
GbKksEFF4yrVs6il55v6gwY5aVje5f0j  
  
  
**Bandit Level 20 → Level 21**  
ssh bandit20@bandit.labs.overthewire.org -p 2220  
`terminal1:` echo GbKksEFF4yrVs6il55v6gwY5aVje5f0j | nc -l -p 9999  
`terminal2:` ./suconnect 9999  
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr  
  
  
**Bandit Level 21 → Level 22**  
ssh bandit21@bandit.labs.overthewire.org -p 2220  
`cron + tab`  
`cronjob_bandit22.shcronjob_bandit23.shcrontab`  
cronjob_bandit22.sh  
`
chmod: changing permissions of '/tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv': Operation not permitted  
/usr/bin/cronjob_bandit22.sh: line 3: /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv: Permission denied  
`  
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv  
Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI  
  
  
**Bandit Level 22 → Level 23**  
ssh bandit22@bandit.labs.overthewire.org -p 2220  
cd /etc/cron.d/  
cat cronjob_bandit23  
cat /usr/bin/cronjob_bandit23.sh  
echo I am user bandit23 | md5sum | cut -d ' ' -f 1  
cat /tmp/8ca319486bfbbc3663ea0fbe81326349  
jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n  
  
  
**Bandit Level 23 → Level 24**  
ssh bandit23@bandit.labs.overthewire.org -p 2220  
cd /etc/cron.d/  
cat cronjob_bandit24  
cat /usr/bin/cronjob_bandit24.sh  
mkdir /tmp/dir_name  
cd /tmp/dir_name  
vim script.sh  
`
#!/bin/sh  
cat /etc/bandit_pass/bandit24 > /tmp/dir_name/password  
`  
chmod 777 script.sh  
chmod -R 777 /tmp/dir_name  
cp script.sh /var/spool/bandit24/  
ls  
`script.shpassword`  
cat password  
UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ  
  
  
**Bandit Level 24 → Level 25**  
ssh bandit24@bandit.labs.overthewire.org -p 2220  
mkdir /tmp/dir_name  
cd /tmp/dir_name  
vim script.sh
`
#!/bin/bash  
password24=UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ  
for i in {0000..9999}  
  do  
    echo $password24 $i >> passlist.txt  
  done  
`  
cat passlist.txt | nc localhost 30002
uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG