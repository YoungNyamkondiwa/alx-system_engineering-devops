0. Hello World  echo "Hello,World"   script that prints “Hello, World”, followed by a new line to the standard output.
1. Confused smiley echo echo \"\(Ôo\)\'  a script that displays a confused smiley "(Ôo)'.
2. Let's display a file  cat /etc/passwd   Display the content of the /etc/passwd file.
3. What about 2? cat /etc/passwd /ect/host Display the content of /etc/passwd and /etc/hosts.
4. Last lines of a file  tail /etc/passwd Display the last 10 lines of /etc/passwd.
5. I'd prefer the first ones actually head /etc/passwd Display the first 10 lines of /etc/passwd.
5. I'd prefer the first ones actually head /etc/passwd Display the first 10 lines of /etc/passwd.                                     
6. Line #2   head -n 3 iacta | tail -n 1   a script that displays the third line of the file iacta.                                   
7. It is a good file that cuts iron without making a noise \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)                                     
8. Save current state of directory  ls -la > ls_cwd_content Putting contents into the file. 
9. Duplicate last line    tail -n 1 iacta | cat >> iacta  script that duplicates the last line of the file iacta
10. No more javascript script that deletes all the regular files (not the directories) with a .js
11. Don't just count your directories, make your directories count find . -mindepth 1 -type d | wc -l  script that counts the number of directories and sub-directories in the current directory.
12. What’s new  ls -t | head script that displays the 10 newest files in the current directory.
13. Being unique is better than being perfect sort | uniq -u script that takes a list of words as input and prints only words that appear exactly once.
14. It must be in that file grep root /etc/passwd  Display lines containing the pattern “root” from the file /etc/passwd
15. Count that word grep bin /etc/passwd Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16. What's next?  Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17. I hate bins grep -v -i "bin" Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18. Letters only please 18. Display all lines of the file /etc/ssh/sshd_config starting with a letter.
19. A to Z Replace all characters A and c from input to Z and e respectively. tr 'Ac' 'Ze'
20. Without C, you would live in hiago tr -d Cc script that removes all letters c and C from input.
21. esreveR   rev  script that reverse its input.
22. DJ Cut Killer        cut -d":" --fields=1,6 /etc/passwd | sort script that displays all users and their home directories, sorted by users.
25. Acrostic echo -ne $(cut -c-1 | tr -d '\n')'\n'     script that decodes acrostics that use the first letter of each line.
26. The biggest fan   tail -n +2 | cut -f1 | sort | uniq -c | sort -nr -k 1,1 | cut -c 9- | head -11   script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
