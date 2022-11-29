# Bash-like-shell

Assignment for NodeJS Developer Internship at Atri Labs

Commands:

1) cd <directory_name> - Should work same as bash shell.
2) pwd - Prints current working directory.
3) ls <directory_name> - Should work same as bash shell. Support for flags is not required.
4) <path_to_binary> <args>- When path to a binary is provided, that binary should be spawned as a child process. The binary must receive all the arguments passed as space separated like arg1 arg2 ….
5) fg <pid> - Brings the background process with process id <pid> to foreground.
6) exit - Closes the shell.

  
  Key-Press
  
  1) Ctrl + C - Sends a SIGINT to the spawned process.
  2) Ctril + Z - Sends spawned process that is currently in foreground to the background. Prints it’s pid after setting the current process as background process.
  
  
Running the shell
  
Start the shell using node shell.js

The shell starts with its default working directory set to user’s home directory.
  
  Test cases
node app.js : Runs a NodeJs script named app.js in the current working directory of the app.
  
  References:
  
  https://www.youtube.com/watch?v=ASrUNNi1q84
  https://nodejs.org/api/process.html
  https://nodejs.org/api/child_process.html
