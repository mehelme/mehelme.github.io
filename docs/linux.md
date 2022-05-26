# Linux

## Команды
Сервисы: ``systemctl list-units --type service`` ``sudo systemctl disable apache``</br>
Перезапуск сети: ``sudo nmcli networking off && sudo nmcli networking on``

## Статьи
PostgreSQL 10 on Ubuntu 16.04 [&#128279;](https://tecadmin.net/install-postgresql-server-on-ubuntu/) </br>
ssh sudo: no tty present and no askpass program specified [&#128279;](https://stackoverflow.com/questions/21659637/how-to-fix-sudo-no-tty-present-and-no-askpass-program-specified-error) </br>
How to record output to speakers [&#128279;](https://askubuntu.com/questions/229352/how-to-record-output-to-speakers) </br>
Шифрование диска [&#128279;](https://stackoverflow.com/questions/19713918/how-to-load-luks-passphrase-from-usb-falling-back-to-keyboard) [&#128279;](https://gist.github.com/martijnvermaat/2726386) </br>
Отправка почты из командной строки [&#128279;](https://blog.edmdesigner.com/send-email-from-linux-command-line/) [&#128279;](https://sites.google.com/site/admcrib/home/ssmtp-nastrojka-dla-yandex-ru) </br>
Загрузка ядра Linux. Часть 1 [&#128279;](https://habr.com/post/428664/) [&#128279;](https://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-1.html) </br>
Магия SSH [&#128279;](https://habr.com/post/331348/) </br>
Выявляем процессы с дисковой активностью в Linux [&#128279;]( https://habr.com/ru/post/476414/ ) </br>

## Настройка
1. GRUB_CMDLINE_LINUX_DEFAULT="nomodeset noresume no_console_suspend ignore_loglevel mitigations=off"
1. /etc/default/locale LC_MESSAGES="C"



