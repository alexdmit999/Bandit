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
