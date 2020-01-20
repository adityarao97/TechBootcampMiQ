# Basic Linux Commands
+ pwd = present working directory
+ ls = file listing
+ ls -l = long listing (9 different parameters)
+ ls -lrt = long listing, reverse order, time sorted
+ bin contains all the executables 
+ etc contains all the configuration files
+ dev contains all the devices 
+ chmod 777 file= to change file/directory permissions 
   - 4 : read
   - 2 : write
   - 1 : execute
+ grep = global regular expression
+ ls -l | grep ^d = prints lines which start with d
+ ls -l | grep ^d.*s$ = prints lines which start with d and ends with s
+ cat -n = prints file with line no
+ tac = prints file in reverse order
+ head /etc/passwd = prints the 1st ten lines
+ tail /etc/passwd = prints the last ten lines
+ tail -2 /etc/passwd = prins the last two lines 
+ man ls = explains what ls can do
+ cat /etc/passwd | cut -d : -f1,2,3,4 = prints the 1st,2nd,3rd and 4th column seperated by ':'
+ cat /etc/passwd | cut -d : -f1,2,3,4 | tr ':' '-'= prints the 1st,2nd,3rd and 4th column seperated by ':' and replaces ':' with '-'
+ cat /etc/passwd | sort | uniq = sorts contents and prints unique items
+ for i in {1..10}
    - do 
    - echo $i
    - done
    - =to print 1st 10 no.s
+ sed = stream editor
+ find . -type f -name "*.csv" = searches for a file in the current directory which ends with .csv
# Git
+ git status = to preview status of git
+ git fetch = to fetch all the codes from all the branches
+ git checkout develop = swithces to a different branch i.e develop
+ git diff . = to show all changes made in the current directory
+ git add . = to add all files of the current directory in the staging area
+ git commit -m "commit text" = to commit changes  
+ git log = lists out all the commits
+ git commit -m "commit text" = to commit changes  
