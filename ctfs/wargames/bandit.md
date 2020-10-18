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
