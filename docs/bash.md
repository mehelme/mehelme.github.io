# Bash 

Печать перевода строки: printf "hello\nworld\n"
Замена перевода строк на пробел: tr '\n' ' ' 
Проверка строки на число:  if [ "$var" -eq "$var" ] 2>/dev/null; then;  echo number; else;  echo not a number; fi
Сравнение чисел: if (( a > b )); then ... для старых if [ "$a" -gt "$b" ]; then ...
Деление: echo $((x / y))

Monitor a file with tail with timestamps added http://www.commandlinefu.com/commands/view/7156/monitor-a-file-with-tail-with-timestamps-added
lower UPPER case convert http://stackoverflow.com/questions/2264428/converting-string-to-lower-case-in-bash-shell-scripting
string padding http://stackoverflow.com/questions/4409399/padding-characters-in-printf
все аргументы http://stackoverflow.com/questions/12314451/accessing-bash-command-line-args-vs
удаленно запустить локальный скрипт http://stackoverflow.com/questions/305035/how-to-use-ssh-to-run-a-shell-script-on-a-remote-machine
Simple logical operators in Bash https://stackoverflow.com/questions/6270440/simple-logical-operators-in-bash