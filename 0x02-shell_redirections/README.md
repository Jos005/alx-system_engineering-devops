# Shell, I/O Redirections and filters

Task 0. echo "Hello, World" - is a script that prints or display “Hello, World”.

Task 1. echo "\"(Ôo)'" - is a script that displays a confused smiley "(Ôo)'

Task 2. cat /etc/passwd - is a script that that displays the content of the /etc/passwd file

Task 3. cat /etc/passwd /etc/hosts - is a script that displays content of /etc/passwd and /etc/hosts

Task 4. tail /etc/passwd - displays the last 10 lines of /etc/passwd

Task 5. head /etc/passwd - displays the first 10 lines of /etc/passwd

Task 6. head -3 iacta | tail -1 - displays the third line of the file iacta

Task 7. echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\*$\\\?\\\*\\\*\\\*\\\*\\\*\:\) - creates a file \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School

Task 8. ls -la > ls_cwd_content - overwrites the contents of the file

Task 9. tail -1 iacta >> iacta - duplicates the last line of the file

Task 10. find . -type f -name "*.js" -delete - deletes all files with a .js extending to current directory and subfolders

Task 11. find . -type d ! -path . | wc -l - counts the number of directories and sub-directories

Task 12. ls -t . | head - displays the 10 newest files in the current directory

Task 13. sort | uniq -u - takes a list of words as input and prints only words that appear exactly once

Task 14. egrep "root" /etc/passwd - displays lines containing the pattern root from the file /etc/passwd

Task 15. egrep -i "bin" /etc/passwd | wc -l - displays number of lines that contain the pattern bin in the file /etc/passwd

Task 16 grep -iA 3 "root" /etc/passwd - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

Task 17. grep -v "bin" /etc/passwd - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”

Task 18. grep -i '^[a-z]' /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter.

Task 19. tr "A" "Z" | tr "c" "e" - Replace all characters A and c from input to Z and e respectively.

Task 20. tr -d "Cc" - removes all letters c and C from input.

Task 21. rev - reverse its input.

Task 22. cut -d ":" -f1,6 /etc/passwd | sort - displays all users and their home directories, sorted by users 
