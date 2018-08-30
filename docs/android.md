# Android

Выключить selinux: setenforce 0
Список пакетов:  pm list packages -f
Получить версию пакета (shell): dumpsys package ru.yandex.yandexmaps | grep version
Получить версию пакета (sdk): aapt dump badging /data/app/ru.yandex.yandexmaps-1.apk | grep package

Получить контакты:
content query --uri content://contacts/phones --projection number:name --sort "name ASC"| awk -F= '{gsub(/[-() name]/,"",$2);print $2" "$3}'

Решение проблемы быстрого расхода батареи на Android из-за процесса MediaServer https://ekorshunov.blogspot.ru/2015/02/android-mediaserver.html

Скрипты на shell под Android, Пишем-обсуждаем резиденты и прочие в быту полезные команды </br> <https://4pda.ru/forum/index.php?showtopic=508427>

Freeing my tablet (Android hacking, SW and HW) </br> <https://www.thanassis.space/android.html>
Ломаем Android. Как глубока кроличья нора? </br> <https://habrahabr.ru/post/320150/>