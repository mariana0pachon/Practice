# Over The Wire
## Level 0
ssh bandit0@bandit.labs.overthewire.org -p 2220
bandit 0
cat readme


## Level 1 -> 2
ssh bandit1@bandit.labs.overthewire.org -p 2220
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
cat ./-


## Level 2 -> 3
ssh bandit2@bandit.labs.overthewire.org -p 2220
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
cat "spaces in this filename"


## Level 3 -> 4
ssh bandit3@bandit.labs.overthewire.org -p 2220
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
cd inhere
ls -a
cat .hidden


## Level 4 -> 5
ssh bandit4@bandit.labs.overthewire.org -p 2220
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
file ./*
cat ./file07


## Level 5 -> 6
ssh bandit5@bandit.labs.overthewire.org -p 2220
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
find ./* -size 1033c
cat ./maybehere07/ .file2


## Level 6 -> 7
ssh bandit6@bandit.labs.overthewire.org -p 2220
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password

## Level 7 -> Level 8
ssh bandit7@bandit.labs.overthewire.org -p 2220
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
grep -r "millionth"  "data.txt"


## Level 8 -> Level 9
ssh bandit8@bandit.labs.overthewire.org -p 2220
cvX2JJa4CFALtqS87jk27qwqGhBM9plV
sort data.txt | uniq -u


## Level 9 -> Level 10 
ssh bandit9@bandit.labs.overthewire.org -p 2220
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

