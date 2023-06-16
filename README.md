# shell_script
outpt of commands 
$# -- total no of paramenters passed to shell scripts 
$1 --fist parameter 


if else 

if [ expression ]
then
   statement1
else
   statement2
fi

==========
for loop 

for variableName in item1 item2 item3 item4 item5 item6
do
   echo "${variableName}"
done

====
while loop

#!/bin/bash
file_path="/etc/passwd"
while read line
do
    echo "$line"
    sleep 0.20
done < $file_path

============
