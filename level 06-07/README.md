ssh bandit6@bandit.labs.overthewire.org -p 2220             // to enter level 6
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null   //to search the entire system for file owned by bandit7, group bandit6, size 33 bytes
cat /var/lib/dpkg/info/bandit7.password                     // to read the passwordfile
// the password shown -morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
exit                                                        // to exit the level 6
