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

## Установка и настройка kubuntu 1804
1. Настройка статический ip
1. Установка mc (конфиги)
1. Настройка шрифта konsole
1. Настройки в центре настроек kde: убрана анимация, раскладка, шрифт, рабочие столы, убран поиск plasma, выкл бумажник, пути на eng, выкл эффектов, автомонтирование usb флешек
1. /etc/default/locale LC_MESSAGES="C"
1. /etc/polkit-1/localauthority/50-local.d/com.ubuntu.enable-hibernate.pkla (для нормальной работы загрузчик должен грузится из bios, не через другой )
1. установка дров nvidia, почему то сразу не встало, нужно в консоле ```sudo dpkg --configure -a``` см. [&#128279;](https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-18-04-bionic-beaver-linux)
1. монтирование дисков других
1. thunderbird
1. ссылки на каталоге из andrey
1. ссылки .cache .config, fontconfig
1. шрефты (+gtk приложения chrome, thunderbird)
1. удалить akonadi
1. vmware
1. trac
1. ftp
1. необходимые dev пакеты
1. настройки из etc (apport, cron, sysctl.conf)
1. проверить создание корок
1. ssh
1. kate
1. таймаут повтора клавы 250
1. опера почемуто стала дефолтным бразуером, изменил ~/.config/mimeapps.list и сделал ссылку в ~/.local/share/applications
1. qstardict (перехватывает Ctrl+T и браузер не мог табу новую открыть)


