# Android

## В работе
История уведомлений: <code>android.settings.notification.history.NotificationHistoryActivity</code><br>

## Команды
Выключить selinux: <code>setenforce 0</code><br>
Список пакетов:  <code>pm list packages -f</code><br>
Версия пакета (shell): <code>dumpsys package ru.yandex.yandexmaps | grep version</code><br>
Версия пакета (sdk): <code>aapt dump badging /data/app/ru.yandex.yandexmaps-1.apk | grep package</code><br>
Получить контакты:<code>content query --uri content://contacts/phones --projection number:name --sort "name ASC"| awk -F= '{gsub(/[-() name]/,"",$2);print $2" "$3}'</code><br>

## Статьи
Решение проблемы быстрого расхода батареи из-за MediaServer [&#128279;](https://ekorshunov.blogspot.ru/2015/02/android-mediaserver.html)<br>
Скрипты на shell под Android 4pda [&#128279;](https://4pda.ru/forum/index.php?showtopic=508427)<br>
Freeing my tablet (Android hacking, SW and HW) [&#128279;](https://www.thanassis.space/android.html)<br>
Ломаем Android. Как глубока кроличья нора? [&#128279;](https://habrahabr.ru/post/320150/>)<br>
Cохранение фото на SD карту [&#128279;](https://opencamera.sourceforge.io/help.html)<br>
Кросс-компиляция (mc)
[&#128279;](http://tetraquark.ru/archives/10)
[&#128279;](http://dp.nonoo.hu/cross-compiling-mc/)
[&#128279;](https://zwyuan.github.io/2016/07/17/cross-compile-glib-for-android/) <br>
Cron и добавление скрипта в автозапуск [&#128279;]( https://habr.com/ru/post/468337/ ) <br>

## Удаление системных приложений
Тема 4pda [&#128279;](http://4pda.ru/forum/index.php?showtopic=236256) <br>
```
setenforce 0
mount -o rw,remount /system
mount -o rw,remount /
pm list packages -f
rm /system/app/YouTube.apk
pm uninstall com.android.mms
for p in `pm list package | awk -F"package:" '{print $2}'`; do echo -n "$p: "; dumpsys package $p | grep -i versionName | awk -F"=" '{print $2}'; done
/system/priv-app/
/system/vendor/operator/app/
```