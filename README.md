# far2l-deb
.deb пакеты [far2l](https://github.com/elfmz/far2l) (linux порт [Far Manager 2](http://www.farmanager.com/index.php?l=en), включая FTP/SFTP/WebDAV/SMB клиент [far-gvfs](https://github.com/cycleg/far-gvfs)).

Пакеты собираются для Mint 18.1 / Ubuntu 16.04.2 под архитектуры i386 и amd64.

На debian jessie вы можете собрать пакет самостоятельно, используя скрипт make_far2l_deb.sh.

На более старых дистрибутивах это скрипт, возможно, тоже будет работать, хотя не факт.

Если у вас не завелось - пишите тикет, возможно, я смогу с этим что-нибудь сделать (или нет).

---
```
wget -O far2l_64.deb https://github.com/evgenyk/far2l-deb/blob/master/far2l_64_tty_18_04.deb?raw=true ; sudo dpkg -i ./far2l_64.deb ; sudo apt-get install -f
```
---

.deb packages for [far2l](https://github.com/elfmz/far2l) ([Far Manager 2](http://www.farmanager.com/index.php?l=en) linux port, including [far-gvfs](https://github.com/cycleg/far-gvfs) plugin as FTP/SFTP/WebDAV/SMB client).

Confirmed working on Mint 18.1 / Ubuntu 16.04.2 (i386 & amd64 builds available).

On debian jessie use make_far2l_deb.sh.

On older distros make_far2l_deb.sh may or may not work.

Feel free to report any issues.
