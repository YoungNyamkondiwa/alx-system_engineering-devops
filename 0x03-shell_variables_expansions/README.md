0. <o> script that creates an alias.   Name: ls --Value: rm *.      alias ls="rm *"
1. Hello you script that prints hello user, where user is the current Linux user.       echo "hello $USER"
2. The path to success is to take massive, determined action  Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.       PATH=$PATH:/action.
3. If the path be beautiful, let us not ask where it leads. script that counts the number of directories in the PATH.        echo $PATH | tr ":" "\n" | wc -l.
4. Global variables  script that lists environment variables.    printenv.
5. Local variables  script that lists all local variables and environment variables, and functions.      set.
6. Local variable   script that creates a new local variable. BEST=School.
7. Global variable  script that creates a new global variable.    export BEST=School.
8. Every addition to true knowledge is an addition to human power   script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.             echo $(($TRUEKNOWLEDGE+128))
9. Divide and rule    script that prints the result of POWER divided by DIVIDE, followed by a new line.  POWER and DIVIDE are environment variables    echo $(($POWER/$DIVIDE)).
10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath.script that displays the result of BREATH to the power LOVE  BREATH and LOVE are environment variables   The script should display the result, followed by a new line   echo $(($BREATH**$LOVE)).
11. There are 10 types of people in the world -- Those who understand binary, and those who don't      script that converts a number from base 2 to base 10.   The number in base 2 is stored in the environment variable BINARY  .The script should display the number in base 10, followed by a new line        echo "$((2#$BINARY))".
12. Combination     Create a script that prints all possible combinations of two letters, except oo.        echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo.
13. Floats     script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.      printf "%0.2f\n" $NUM
