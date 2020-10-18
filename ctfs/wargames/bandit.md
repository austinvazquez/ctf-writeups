# [Bandit](https://overthewire.org/wargames/bandit/)

## SSH Information

- Host: bandit.labs.overthewire.org
- Port: 2220

## Levels

### [Level 0](https://overthewire.org/wargames/bandit/bandit1.html)

1. SSH to the server.
2. cat readme

boJ9jbbUNNfktd78OOpsqOltutMc3MY1

### [Level 1](https://overthewire.org/wargames/bandit/bandit2.html)

1. SSH to the server.
2. cat ./-

CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

### [Level 2](https://overthewire.org/wargames/bandit/bandit3.html)

1. SSH to the server.
2. cat "spaces in this filename"

UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

### [Level 3](https://overthewire.org/wargames/bandit/bandit4.html)

1. SSH to the server.
2. cat inhere/.hidden

pIwrPrtPN36QITSp3EQaw936yaFoFgAB

### [Level 4](https://overthewire.org/wargames/bandit/bandit5.html)

1. SSH to the server.
2. cat $(find inhere/ -not -name *.htaccess)

koReBOKuIDDepwhWk7jZC0RTdopnAYKh

### [Level 5](https://overthewire.org/wargames/bandit/bandit6.html)

1. SSH to the server.
2. find . -type f -size 1033c -exec cat {} \;

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

### [Level 6](https://overthewire.org/wargames/bandit/bandit7.html)

1. SSH to the server.
2. find / -user bandit7 -group bandit6 -type f -size 33c -exec cat {} \;

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

### [Level 7](https://overthewire.org/wargames/bandit/bandit8.html)

1. SSH to the server.
2. cat data.txt | grep "millionth"

cvX2JJa4CFALtqS87jk27qwqGhBM9plV

### [Level 8](https://overthewire.org/wargames/bandit/bandit9.html)

1. SSH to the server.
2. cat data.txt | sort | uniq -u

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

### [Level 9](https://overthewire.org/wargames/bandit/bandit10.html)

1. SSH to the server.
2. strings data.txt

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

### [Level 10](https://overthewire.org/wargames/bandit/bandit11.html)

1. SSH to the server.
2. base64 -d data.txt

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

### [Level 11](https://overthewire.org/wargames/bandit/bandit12.html)

1. SSH to the server.
2. cat data.txt | tr "A-Za-z" "N-ZA-Mn-za-m"

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

### [Level 12](https://overthewire.org/wargames/bandit/bandit13.html)

1. SSH to the server.
2. mkdir /tmp/madscientist
3. cp data.txt /tmp/madscientist
4. cd /tmp/madscientist
5. xxd -r data.txt data
6. file data
7. mv data{,.gz}
8. gunzip data.gz
9. file data
10. bzip2 -d data
11. file data.out
12. mv data.out data.gz
13. gunzip data.gz
14. file data
15. mv data data.tar
16. tar -xvf data.tar
17. file data5.bin
18. mv data5.bin data5.tar
19. tar -xvf data5.tar
20. file data6.bin
21. bzip2 -d data6.bin
22. file data6.bin.out
23. mv data6.bin.out data6.tar
24. tar -xvf data6.tar
25. file data8.bin
26. mv data8.bin data8.gz
27. gunzip data8.gz
28. cat data8

8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

### [Level 13](https://overthewire.org/wargames/bandit/bandit14.html)

1. SSH to the server.
2. ssh -i sshkey.private bandit14@localhost

### [Level 14](https://overthewire.org/wargames/bandit/bandit15.html)

1. SSH to the server.
2. cat /etc/bandit_pass/bandit14 | nc localhost 30000

BfMYroe26WYalil77FoDi9qh59eK5xNr

### [Level 15](https://overthewire.org/wargames/bandit/bandit16.html)

1. SSH to the server.
2. cat /etc/bandit_pass/bandit15 | openssl s_client -connect localhost:30001 -ign_eof

cluFn7wTiGryunymYOu4RcffSxQluehd
