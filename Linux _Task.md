Bandit Task

Level 0 :
username : bandit0
password : bandit0

commands used : ssh bandit0@bandit.labs.overthewire.org -p 2220


Level 1 : 
password :  ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
commands used : 
ls
cat readme
exit
ssh bandit1@bandit.labs.overthewire.org -p 2220

 

Level 2 :
password : 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
commands used : 
cat ./- 
exit
ssh bandit2@bandit.labs.overthewire.org -p 2220
 exit 



Level 3 :

password : MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
commands used :
cat spaces/ in /this /filename
exit 
ssh bandit3@bandit.labs.overthewire.org -p 2220

 

Level 4 : 
password : 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

commands used : 
cd inhere
cat ...Hidden-From-You
exit 
ssh bandit4@bandit.labs.overthewire.org -p 2220

 

Level 5 :
password : 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
commands used :
cd inhere
ls
cat (each file until a file was readable) --> cat ./-file07
exit
ssh bandit5@bandit.labs.overthewire.org -p 2220

 

level 6 :

password : HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
commands used :

cd (for each directory) then ls -la and search until found then cat maybehere07
or 
search for the file in the inhere directory 
. -find -type f -size 1033 ! -executable
exit
ssh bandit6@bandit.labs.overthewire.org -p 2220

Level 7 :
password : morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

commands used : 
find / -type f -user  bandit7 -group bandit6 -size 33c 
cat /var/lib/dpkg/info/bandit7.password
exit 
ssh bandit8@bandit.labs.overthewire.org -p 2220
 


Level 8 :

password : dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
commands used :
cat data.txt | grep millionth
exit 
ssh bandit8@bandit.labs.overthewire.org -p 2220



level 9 :
password : 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

commands used :
sort data.txt | uniq -u
exit 
ssh bandit9@bandit.labs.overthewire.org -p 2220



Level 10 :
password : FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

commands used : 
cat data.txt and `search for a readable string 
or
strings data.txt | grep "=" 
exit 
ssh bandit10@bandit.labs.overthewire.org -p 2220

 

Level 11 : 
password : dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
commands used :
cat data.txt | base64 -d
exit
ssh bandit11@bandit.labs.overthewire.org -p 2220

level 12 : 

password : 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

commands used : 
cat data.txt | tr 'a-zA-Z' 'n-za-mN-ZA-M' which translates the charachers rotated 13 positions 
or cat data.txt | tr and use an outsider source to translate the upcoming string
exit
ssh bandit12@bandit.labs.overthewire.org -p 2220
