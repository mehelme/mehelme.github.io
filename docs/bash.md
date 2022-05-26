# Bash

## Команды
Печать перевода строки: <code>printf "hello\nworld\n"</code><br>
Замена перевода строк на пробел: <code>tr '\n' ' ' </code><br>
Проверка строки на число:  <code>if [ "$var" -eq "$var" ] 2>/dev/null; then; echo IS NIMBER fi</code><br>
Сравнение чисел: <code>if (( a > b )); then ... if [ "$a" -gt "$b" ]; then ...</code><br>
Деление: <code>echo $((x / y))</code><br>
Хаки SSH [&#128279;]( https://www.shellhacks.com/start-gui-application-remote-computer-ssh/) <br>

## Статьи
Добавить "ДатаВремя" к каждой строке [&#128279;](http://www.commandlinefu.com/commands/view/7156/monitor-a-file-with-tail-with-timestamps-added)
    [&#128279;](https://unix.stackexchange.com/questions/26728/prepending-a-timestamp-to-each-line-of-output-from-a-command)<br>
lower UPPER case convert [&#128279;](http://stackoverflow.com/questions/2264428/converting-string-to-lower-case-in-bash-shell-scripting)<br>
Выравнивание строк [&#128279;](http://stackoverflow.com/questions/4409399/padding-characters-in-printf)<br>
Все аргументы "$@ vs $*" [&#128279;](http://stackoverflow.com/questions/12314451/accessing-bash-command-line-args-vs)<br>
Удаленно запустить локальный скрипт [&#128279;](http://stackoverflow.com/questions/305035/how-to-use-ssh-to-run-a-shell-script-on-a-remote-machine)<br>
Simple logical operators in Bash [&#128279;](https://stackoverflow.com/questions/6270440/simple-logical-operators-in-bash)<br>
