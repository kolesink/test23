# test23
На стендовой виртуальной машине создадим 3х пользователей
”day” “night” “friday” изменим настройки модуля pam_time, для гибкой настройки доступ
пользователя с учетом времени,  хранятся в файле /etc/security/time.conf 
*;*;day;Al0800-2000
*;*;night;!Al0800-2000
*;*;friday;Fr
в данный период времени доступ разрешен всем
![Image text](https://github.com/kolesink/test23/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-08-09%2021-26-40.png)
![Image text](https://github.com/kolesink/test23/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202022-08-09%2021-29-07.png)
