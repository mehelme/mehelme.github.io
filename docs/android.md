# Android

## Команды
Выключить selinux: <code>setenforce 0</code></br>
Список пакетов:  <code>pm list packages -f</code></br>
Получить версию пакета (shell): <code>dumpsys package ru.yandex.yandexmaps | grep version</code></br>
Получить версию пакета (sdk): <code>aapt dump badging /data/app/ru.yandex.yandexmaps-1.apk | grep package</code></br>
Получить контакты:<code>content query --uri content://contacts/phones --projection number:name --sort "name ASC"| awk -F= '{gsub(/[-() name]/,"",$2);print $2" "$3}'</code></br>

## Статьи
Решение проблемы быстрого расхода батареи на Android из-за процесса MediaServer [&#128279;](https://ekorshunov.blogspot.ru/2015/02/android-mediaserver.html)
Скрипты на shell под Android 4pda [&#128279;](https://4pda.ru/forum/index.php?showtopic=508427)
Freeing my tablet (Android hacking, SW and HW) [&#128279;](https://www.thanassis.space/android.html)
Ломаем Android. Как глубока кроличья нора? [&#128279;](https://habrahabr.ru/post/320150/>)
