# [Bandit](https://overthewire.org/wargames/bandit/)

## SSH Information

```
Host: bandit.labs.overthewire.org
Port: 2220
```

## Levels

### [Level 0](https://overthewire.org/wargames/bandit/bandit1.html)

```sh
cat readme
```

boJ9jbbUNNfktd78OOpsqOltutMc3MY1

### [Level 1](https://overthewire.org/wargames/bandit/bandit2.html)

```sh
cat ./-
```

CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

### [Level 2](https://overthewire.org/wargames/bandit/bandit3.html)

```sh
cat "spaces in this filename"
```

UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

### [Level 3](https://overthewire.org/wargames/bandit/bandit4.html)

```sh
cat inhere/.hidden
```

pIwrPrtPN36QITSp3EQaw936yaFoFgAB

### [Level 4](https://overthewire.org/wargames/bandit/bandit5.html)

```sh
cat $(find inhere/ -not -name *.htaccess)
```

koReBOKuIDDepwhWk7jZC0RTdopnAYKh

### [Level 5](https://overthewire.org/wargames/bandit/bandit6.html)

```sh
find . -type f -size 1033c -exec cat {} \;
```

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

### [Level 6](https://overthewire.org/wargames/bandit/bandit7.html)

```sh
find / -user bandit7 -group bandit6 -type f -size 33c -exec cat {} \;
```

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

### [Level 7](https://overthewire.org/wargames/bandit/bandit8.html)

```sh
cat data.txt | grep "millionth"
```

cvX2JJa4CFALtqS87jk27qwqGhBM9plV

### [Level 8](https://overthewire.org/wargames/bandit/bandit9.html)

```sh
cat data.txt | sort | uniq -u
```

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

### [Level 9](https://overthewire.org/wargames/bandit/bandit10.html)

```sh
strings data.txt
```

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

### [Level 10](https://overthewire.org/wargames/bandit/bandit11.html)

```sh
base64 -d data.txt
```

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

### [Level 11](https://overthewire.org/wargames/bandit/bandit12.html)

```sh
cat data.txt | tr "A-Za-z" "N-ZA-Mn-za-m"
```

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

### [Level 12](https://overthewire.org/wargames/bandit/bandit13.html)

```sh
mkdir /tmp/madscientist
cp data.txt /tmp/madscientist
cd /tmp/madscientist
xxd -r data.txt data
file data
mv data{,.gz}
gunzip data.gz
file data
bzip2 -d data
file data.out
mv data.out data.gz
gunzip data.gz
file data
mv data data.tar
tar -xvf data.tar
file data5.bin
mv data5.bin data5.tar
tar -xvf data5.tar
file data6.bin
bzip2 -d data6.bin
file data6.bin.out
mv data6.bin.out data6.tar
tar -xvf data6.tar
file data8.bin
mv data8.bin data8.gz
gunzip data8.gz
cat data8
```

8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

### [Level 13](https://overthewire.org/wargames/bandit/bandit14.html)

```sh
ssh -i sshkey.private bandit14@localhost
```

### [Level 14](https://overthewire.org/wargames/bandit/bandit15.html)

```sh
cat /etc/bandit_pass/bandit14 | nc localhost 30000
```

BfMYroe26WYalil77FoDi9qh59eK5xNr

### [Level 15](https://overthewire.org/wargames/bandit/bandit16.html)

```sh
cat /etc/bandit_pass/bandit15 | openssl s_client -connect localhost:30001 -ign_eof
```

cluFn7wTiGryunymYOu4RcffSxQluehd

### [Level 16](https://overthewire.org/wargames/bandit/bandit17.html)

```sh
nmap -p 31000-32000 localhost
openssl s_client -connect localhost:31790
vim id_rsa.key
chmod 600 id_rsa.key
ssh -i id_rsa.key bandit17@localhost
cat /etc/bandit_pass/bandit17
```

xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn

### [Level 17](https://overthewire.org/wargames/bandit/bandit18.html)

```sh
diff passwords.old passwords.new
```

kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd

### [Level 18](https://overthewire.org/wargames/bandit/bandit19.html)

```sh
ssh -T bandit18@bandit.labs.overthewire.org -p 2220
```

IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x

### [Level 19](https://overthewire.org/wargames/bandit/bandit20.html)

```sh
./bandit20-do cat /etc/bandit_pass/bandit20
```

GbKksEFF4yrVs6il55v6gwY5aVje5f0j

### [Level 20](https://overthewire.org/wargames/bandit/bandit21.html)

```sh
echo GbKksEFF4yrVs6il55v6gwY5aVje5f0j | nc -l localhost -p 54321 &
./suconnect 54321
```

gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr

### [Level 21](https://overthewire.org/wargames/bandit/bandit22.html)

```sh
cat /etc/cron.d/cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
```

Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI

### [Level 22](https://overthewire.org/wargames/bandit/bandit23.html)

```sh
cat /etc/cron.d/cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
echo I am user bandit23 | md5sum | cut -d ' ' -f 1
cat /tmp/8ca319486bfbbc3663ea0fbe81326349
```

jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n

### [Level 23](https://overthewire.org/wargames/bandit/bandit24.html)

```sh
cat /etc/cron.d/cronjob_bandit24
cat /usr/bin/cronjob_bandit24.sh
vim /var/spool/bandit24/script.sh
chmod 777 /var/spool/bandit24/script.sh
cat /tmp/madscientist
```

UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ

### [Level 24](https://overthewire.org/wargames/bandit/bandit25.html)

```sh
for i in $(seq -f "%04g" 0 9999); do echo "UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ" $i >> /tmp/madscientist; done;
cat /tmp/madscientist | nc localhost 30002 | grep password
```

uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG

### [Level 25](https://overthewire.org/wargames/bandit/bandit26.html)

```sh
ssh -i bandit26.sshkey bandit26@localhost
set shell=/bin/bash
sh
cat /etc/bandit_pass/bandit26
```

5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z
