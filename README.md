run the script install.sh with on those parameters "Red Hat Enterprise"|"CentOS"|"Scientific" |"Ubuntu"|"Debian", if your OS Ubuntu "use apt command" the script will be like that " sh install.sh Ubuntu "


to open/close required ports, open file security.sh in the line 4 "ports=()" of script u can add your ports which u want to open/close, it will be like that ports=(4444 3333 8888), then close your file

to open some ports/port based on the second step, run "sh security.sh add" from shell

to close some ports/port based on the second step, run "sh security.sh remove" from shell



