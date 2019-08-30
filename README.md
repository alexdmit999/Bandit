# Bandit
<p><b>Bandit Level 0</b>
  <br>ssh bandit0@bandit.labs.overthewire.org -p 2220
  <br>bandit0
    </p>
<p><b>Bandit Level 0 → Level 1</b>
  <br>ssh bandit0@bandit.labs.overthewire.org -p 2220
  <br>cat readme
  <br>boJ9jbbUNNfktd78OOpsqOltutMc3MY1
    </p>
<p><b>Bandit Level 1 → Level 2</b>
  <br>ssh bandit1@bandit.labs.overthewire.org -p 2220
  <br>cd /home/
  <br>cat bandit1/-
  <br>CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
    </p>
<p><b>Bandit Level 2 → Level 3</b>
  <br>ssh bandit2@bandit.labs.overthewire.org -p 2220
  <br>cd /home/
  <br>cat bandit2/spaces\ in\ this\ filename
  <br>UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
    </p>
<p><b>Bandit Level 3 → Level 4</b>
  <br>ssh bandit3@bandit.labs.overthewire.org -p 2220
  <br>ls -a
  <br>cat inhere/.hidden
  <br>pIwrPrtPN36QITSp3EQaw936yaFoFgAB
    </p>
<p><b>Bandit Level 4 → Level 5</b>
  <br>ssh bandit4@bandit.labs.overthewire.org -p 2220
  <br>file -m inhere/
  <br>koReBOKuIDDepwhWk7jZC0RTdopnAYKh
    </p>
<p><b>Bandit Level 5 → Level 6</b>
  <br>ssh bandit5@bandit.labs.overthewire.org -p 2220
  <br>find inhere/ -type f -size 1033c
  <br>cat [filepath]
  <br>DXjZPULLxYr17uwoI01bNLQbtFemEgo7
    </p>
<p><b>Bandit Level 6 → Level 7</b>
  <br>ssh bandit6@bandit.labs.overthewire.org -p 2220
  <br>find / -type f -user bandit7 -group bandit6 -size 33c [-ls]
  <br>cat 'filepath'
  <br>HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
    </p>
<p><b>Bandit Level 7 → Level 8</b>
  <br>ssh bandit7@bandit.labs.overthewire.org -p 2220
  <br>grep -n millionth data.txt 
  <br>cvX2JJa4CFALtqS87jk27qwqGhBM9plV
    </p>
<p><b>Bandit Level 8 → Level 9</b>
  <br>ssh bandit8@bandit.labs.overthewire.org -p 2220
  <br>sort data.txt | uniq -u
  <br>UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
    </p>
<p><b>Bandit Level 9 → Level 10</b>
  <br>ssh bandit9@bandit.labs.overthewire.org -p 2220
  <br>strings -a data.txt
  <br>truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
    </p>
<p><b>Bandit Level 10 → Level 11</b>
  <br>ssh bandit10@bandit.labs.overthewire.org -p 2220
  <br>cat data.txt | base64 -d
  <br>IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
    </p>
<p><b>Bandit Level 11 → Level 12</b>
  <br>ssh bandit11@bandit.labs.overthewire.org -p 2220
  <br>cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
  <br>5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
    </p>
<p><b>Bandit Level 12 → Level 13</b>
  <br>ssh bandit12@bandit.labs.overthewire.org -p 2220
  <br>mkdir /tmp/new_dir
  <br>cp data.txt /tmp/new_dir
  <br>cd /tmp/new_dir
  <br>xxd -r data.txt > data
  <br>file data
  <br>mv data data.gz
  <br>gzip -d data.gz
  <br>file data
  <br>mv data data.bz2
  <br>bzip2 -d data.bz2
  <br>file data
  <br>mv data data.gz
  <br>gzip -d data.gz
  <br>file data
  <br>mv data data.tar
  <br>tar -xvf data.tar
  <br>file data5.bin
  <br>mv data5.bin data.tar
  <br>tar -xvf data.tar
  <br>file data6.bin
  <br>mv data6.bin data.bz2
  <br>bzip2 -d data.bz2
  <br>file data
  <br>mv data data.tar
  <br>tar -xvf data.tar
  <br>file data8.bin
  <br>mv data8.bin data.gz
  <br>gzip -d data.gz
  <br>file data
  <br>cat data
  <br>8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
    </p>
<p><b>Bandit Level 13 → Level 14</b>
  <br>ssh bandit13@bandit.labs.overthewire.org -p 2220
  <br>cat sshkey.private
  <br>copy the KEY and save it to your PC with nano/vim
  <br>close bandit13 connection
  <br>chmod 600 KEY
  <br>ssh -i KEY bandit14@bandit.labs.overthewire.org -p 2220
  <br>4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
    </p>
<p><b>Bandit Level 14 → Level 15</b>
  <br>ssh bandit14@bandit.labs.overthewire.org -p 2220
  <br>cat /etc/bandit_pass/bandit14
  <br>echo 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e | nc localhost 30000
  <br>BfMYroe26WYalil77FoDi9qh59eK5xNr
    </p>
<p><b>Bandit Level 15 → Level 16</b>
  <br>ssh bandit15@bandit.labs.overthewire.org -p 2220
  <br>cat /etc/bandit_pass/bandit15 | openssl s_client -connect localhost:30001 -quiet
  <br>cluFn7wTiGryunymYOu4RcffSxQluehd
    </p>
<p><b>Bandit Level 16 → Level 17</b>
  <br>ssh bandit16@bandit.labs.overthewire.org -p 2220
  <br>nmap localhost -p31000-32000 OR you can use nc -zv localhost 31000-32000 result is the same
  <br>with "echo test | nc -v localhost <'port'>" find the two SSL use ports 31790 and 31518 (they don't answer)
  <br>get RSA_PRIVATE_KEY and save it to your PC
  <br>chmod 600 RSA_PRIVATE_KEY
  <br>xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn
    </p>
<p><b>Bandit Level 17 → Level 18</b>
  <br>ssh bandit17@bandit.labs.overthewire.org -p 2220
  <br>diff passwords.new passwords.old 
  <br>kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
    </p>
<p><b>Bandit Level 18 → Level 19</b>
  <br>ssh -t bandit18@bandit.labs.overthewire.org -p 2220 /bin/sh
  <br>ls
  <br>cat readme 
  <br>IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
    </p>
<p><b>Bandit Level 19 → Level 20</b>
  <br>ssh bandit19@bandit.labs.overthewire.org -p 2220
  <br>./bandit20-do cat /etc/bandit_pass/bandit20
  <br>GbKksEFF4yrVs6il55v6gwY5aVje5f0j
    </p>
<p><b>Bandit Level 20 → Level 21</b>
  <br>ssh bandit20@bandit.labs.overthewire.org -p 2220
  <br>terminal1: echo GbKksEFF4yrVs6il55v6gwY5aVje5f0j | nc -l -p 9999
  <br>terminal2: ./suconnect 9999
  <br>gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
    </p>
<p><b>Bandit Level 21 → Level 22</b>
  <br>ssh bandit21@bandit.labs.overthewire.org -p 2220
  <br>cron + tab
  <br>#cronjob_bandit22.sh  cronjob_bandit23.sh  crontab
  <br>cronjob_bandit22.sh
  <br>#chmod: changing permissions of '/tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv': Operation not permitted
  <br>#/usr/bin/cronjob_bandit22.sh: line 3: /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv: Permission denied
  <br>cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
  <br>Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI
    </p>
<p><b>Bandit Level 22 → Level 23</b>
  <br>ssh bandit22@bandit.labs.overthewire.org -p 2220
  <br>cd /etc/cron.d/
  <br>cat cronjob_bandit23
  <br>cat /usr/bin/cronjob_bandit23.sh
  <br>echo I am user bandit23 | md5sum | cut -d ' ' -f 1
  <br>cat /tmp/8ca319486bfbbc3663ea0fbe81326349
  <br>jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n
    </p>
<p><b>Bandit Level 23 → Level 24</b>
  <br>ssh bandit23@bandit.labs.overthewire.org -p 2220
  <br>cd /etc/cron.d/
  <br>cat cronjob_bandit24
  <br>cat /usr/bin/cronjob_bandit24.sh
  <br>mkdir /tmp/dir_name
  <br>cd /tmp/dir_name
  <br>vim script.sh
  <br>#!/bin/sh
  <br>cat /etc/bandit_pass/bandit24 > /tmp/dir_name/password
  <br>chmod 777 script.sh
  <br>chmod -R 777 /tmp/dir_name
  <br>cp script.sh /var/spool/bandit24/
  <br>ls
  <br>>#script.sh  password
  <br>cat password
  <br>UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ
    </p>