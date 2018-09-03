# Linux

## Установка и настройка kubuntu 1804
1. Настройка статический ip
1. Установка mc (конфиги)
1. Настройка шрифта konsole
1. Настройки в центре настроек kde: убрана анимация, раскладка, шрифт, рабочие столы, убран поиск plasma, выкл бумажник, пути на eng, выкл эффектов, автомонтирование usb флешек
1. /etc/default/locale LC_MESSAGES="C"
1. /etc/polkit-1/localauthority/50-local.d/com.ubuntu.enable-hibernate.pkla (для нормальной работы загрузчик должен грузится из bios, не через другой )
1. установка дров nvidia, почему то сразу не встало, нужно в консоле sudo dpkg --configure -a
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


