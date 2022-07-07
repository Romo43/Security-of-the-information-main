## OverTheWire - Bandit

## Bandit Level 0
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
password: bandit0
```

## Bandit Level 0 → Level 1
```
bandit0@bandit:~$ cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```

## Bandit Level 1 → Level 2
```
bandit1@bandit:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```

## Bandit Level 2 → Level 3
```
bandit2@bandit:~$ cat spaces\ in\ this\ filename
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```

## Bandit Level 3 → Level 4
```
bandit3@bandit:~$ cat .hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```

## Bandit Level 4 → Level 5
```
bandit4@bandit:~$ cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```

## Bandit Level 5 → Level 6
```
bandit5@bandit:~$ find -type f -size 1033c
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```

## Bandit Level 6 → Level 7
```
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```

## Bandit Level 7 → Level 8
```
bandit7@bandit:~$ grep "millionth" data.txt
cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```

## Bandit Level 8 → Level 9
```
bandit8@bandit:~$ cat data.txt | sort | uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```

## Bandit Level 9 → Level 10
```
bandit9@bandit:~$ strings data.txt | grep "="
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
```

## Bandit Level 10 → Level 11
```
bandit10@bandit:~$ cat data.txt | base64 --decode
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```

## Bandit Level 11 → Level 12
```
bandit11@bandit:~$ cat data.txt | tr a-zA-Z n-za-mN-ZA-M
5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
```

## Bandit Level 12 → Level 13
```
bandit12@bandit:~$ zcat data.bin | bzcat | zcat | tar xO | tar xO | bzcat | tar xO | zcat         
8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
```

## Bandit Level 13 → Level 14
```
bandit13@bandit:~$ cat /etc/bandit_pass/bandit14
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```

## Bandit Level 14 → Level 15
```
bandit14@bandit:~$ telnet localhost 30000
BfMYroe26WYalil77FoDi9qh59eK5xNr
```

## Bandit Level 15 → Level 16
```
bandit15@bandit:~$ openssl s_client -ign_eof -connect localhost:30001
cluFn7wTiGryunymYOu4RcffSxQluehd
```

## Bandit Level 16 → Level 17
```
bandit16@bandit:~$ cat /etc/bandit_pass/bandit17
xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn
```

## Bandit Level 17 → Level 18
```
bandit17@bandit:~$ diff passwords.new passwords.old
kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
```

## Bandit Level 18 → Level 19
```
ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat ~/readme"
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
```

## Bandit Level 19 → Level 20
```
bandit19@bandit:~$ ./bandit20-do cat /etc/bandit_pass/bandit20
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
```

## Bandit Level 20 → Level 21
```
bandit20@bandit:~$ ./suconnect 1234
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
```

## Bandit Level 21 → Level 22
```
bandit21@bandit:~$ cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI
```

## Bandit Level 22 → Level 23
```
bandit22@bandit:~$ cat /tmp/8ca319486bfbbc3663ea0fbe81326349
jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n
```

## Bandit Level 23 → Level 24
```
bandit23@bandit:~$ cat pass
UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ
```

## Bandit Level 24 → Level 25
```
bandit24@bandit:~$ ./pincode.sh
uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG
```

## Bandit Level 25 → Level 26
```
:shell
5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z
```

## Bandit Level 26 → Level 27
```
bandit26@bandit:~$ ./bandit27-do cat /etc/bandit_pass/bandit27
3ba3118a22e93127a4ed485be72ef5ea
```

## Bandit Level 27 → Level 28
```
bandit27@bandit:~$ cat README
0ef186ac70e04ea33b4c1853d2526fa2
```

## Bandit Level 28 → Level 29
```
bandit28@bandit:~$ git log -p -1
bbc96594b4e001778eee9975372716b2
```

## Bandit Level 29 → Level 30
```
bandit29@bandit:~$ git log -p -1
5b90576bedb2cc04c86a9e924ce42faf
```

## Bandit Level 30 → Level 31
```
bandit30@bandit:~$ git show secret
47e603bb428404d265f59c42920d81e5
```

## Bandit Level 31 → Level 32
```
bandit31@bandit:~$ git push origin master 47e603bb428404d265f59c42920d81e5
56a9bf19c63d650ce78e6ec0354ee45e
```

## Bandit Level 32 → Level 33
```
bandit32@bandit:~$ cat /etc/bandit_pass/bandit33
c9c3199ddf4121b10cf581a98d51caee
```

## Bandit Level 33 → Level 34
```
bandit33@bandit:~$ cat README.txt
```
