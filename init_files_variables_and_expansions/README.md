0. <o>
mandatory
Create a script that creates an alias.
1. Hello you
mandatory
Create a script that prints hello user, where user is the current Linux user.
2. The path to success is to take massive, determined action
mandatory
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3. If the path be beautiful, let us not ask where it leads
mandatory
Create a script that counts the number of directories in the PATH.
4. Global variables
mandatory
Create a script that lists environment variables.
5. Local variables
mandatory
Create a script that lists all local variables and environment variables, and functions.
6. Local variable
mandatory
Create a script that creates a new local variable.

Name: BEST
Value: School
7. Global variable
mandatory
Create a script that creates a new global variable.

Name: BEST
Value: School
8. Every addition to true knowledge is an addition to human power
mandatory
Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
9. Divide and rule
mandatory
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables
10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
mandatory
Write a script that displays the result of BREATH to the power LOVE

BREATH and LOVE are environment variables
The script should display the result, followed by a new line
11. There are 10 types of people in the world -- Those who understand binary, and those who don't
mandatory
Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line
12. Combination
mandatory
Create a script that prints all possible combinations of two letters, except oo.

Letters are lower cases, from a to z
One combination per line
The output should be alpha ordered, starting with aa
Do not print oo
Your script file should contain maximum 64 characters
13. Floats
mandatory
Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.
14. Decimal to Hexadecimal
mandatory
Write a script that converts a number from base 10 to base 16.

The number in base 10 is stored in the environment variable DECIMAL
The script should display the number in base 16, followed by a new line
15. What happens when you type ls *.c
#advanced
Write a blog post describing step by step what happens when you type ls *.c and hit Enter in your shell. Try to explain every step you know of, and give examples. A total beginner should understand what you have written.

Have at least one picture, at the top of the blog post
Publish your blog post on Medium or LinkedIn
Share your blog post at least on LinkedIn
Write professionally and intelligibly
Please, remember that these blogs must be written in English to further your technical ability in a variety of settings
Remember, future employers will see your articles; take this seriously, and produce something that will be an asset to your future

When done, please add all urls below (blog post, LinkedIn post, etc.)
16. Everyone is a proponent of strong encryption
#advanced
Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.

julien@production-503e7013:~/shell/fun_with_the_shell$ cat quote
"Everyone is a proponent of strong encryption."
- Dorothy E. Denning
julien@production-503e7013:~/shell/fun_with_the_shell$ ./15-rot13 < quote
"Rirelbar vf n cebcbarag bs fgebat rapelcgvba."
- Qbebgul R. Qraavat
julien@production-503e7013:~/shell/fun_with_the_shell$

Write a script that prints every other line from the input, starting with the first line.

ubuntu@ip-172-31-63-244:/$ \ls -1
bin
boot
dev
etc
home
initrd.img
lib
lib32
lib64
libx32
lost+found
media
mnt
opt
proc
root
run
sbin
srv
sys
t
#t#
t~
tmp
usr
var
vmlinuz
whoareyou
ubuntu@ip-172-31-63-244:/$ \ls -1 | ./c-odd
bin
dev
home
lib
lib64
lost+found
mnt
proc
run
srv
t
t~
usr
vmlinuz
ubuntu@ip-172-31-63-244:/$
18. I'm an instant star. Just add water and stir.
#advanced
Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.

WATER is in base water
STIR is in base stir.
The result should be in base bestchol

