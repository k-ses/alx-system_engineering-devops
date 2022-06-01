alias ls="rm *" creates an alias
echo "hello $USER" prints hello user
echo /action adds directory to the $PATH
PATH=$PATH:/action add action directory to the $PATH
$PATH | tr ":" "\n" | wc -l counts the number of directories in the PATH
printenv list environment variables
export BEST="School" create local variable
export BEST="School" create global variable
expr $POWER / $DIVIDE returnsof division between the two variables
echo $(($BREATH**LOVE))





echo "$((2#$BINARY))" converts number fr base 2 to base 10
prints total combinations of two letters echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"
