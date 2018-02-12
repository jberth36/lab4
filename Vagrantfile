#Scripts from Lab 1
#I made one small change to each script

#This script displays the top 5 CPU processes
#!/bin/bash

psss aux --sort -%cpu | head -n 6



#This script lets up update user's passwords
#!/bin/bash

egrep "^$username" /etc/passwd>/dev/null
if [ $? -eq 0 ]; then
    echo "User found!"
    paswd $username
    exit 1
else
    echo "User does not exist on this system."
fi



#This script lets you update the passwords for a list of users from a text file.
#!/bin/bash

for i in `cat /userlist.txt`; do
echo "For user: $i"
passwd $i
@@@done
