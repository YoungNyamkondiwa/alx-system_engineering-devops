0. <o> script that creates an alias.   Name: ls --Value: rm *.      alias ls="rm *"
1. Hello you script that prints hello user, where user is the current Linux user.       echo "hello $USER"
2. The path to success is to take massive, determined action  Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.       PATH=$PATH:/action.
3. If the path be beautiful, let us not ask where it leads. script that counts the number of directories in the PATH.        echo $PATH | tr ":" "\n" | wc -l.
4. Global variables  script that lists environment variables.    printenv
