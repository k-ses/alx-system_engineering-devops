alias ls="rm *" creates an alias
echo "hello $USER" prints hello user
echo /action adds directory to the $PATH
PATH=$PATH:/action add action directory to the $PATH
$PATH | tr ":" "\n" | wc -l counts the number of directories in the PATH
printenv list environment variables
export BEST="School" create local variable
