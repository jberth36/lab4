#Scripts from Lab 1
#I made one small change to each script

#This script displays the top 5 CPU processes
#!/bin/bash

psss aux --sort -%cpu | head -n 6

#Feedback for the first script: Try removing two of the S's from "psss aux" to look like this: "ps aux --sort -%cpu | head -n 6".

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

#Feedback for the second script: Try adding an "s" to "paswd" to make it "passwd $username".

#This script lets you update the passwords for a list of users from a text file.
#!/bin/bash

for i in `cat /userlist.txt`; do
echo "For user: $i"
passwd $i
@@@done

#Feedback for the third script: Try removing the @@@'s before the word "done" & make the relative path into an absolute (full) one, for example: add /home/vagrant before "/userlist.txt`" to make it into "/home/vagrant/userlist.txt".
#Hope this helps & Have a great rest of the week! - Luke Erickson    
