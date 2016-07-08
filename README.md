#URL List For MS-KEY Tool and Garbage Collector

* [MS-KEY Tool](http://bbs.pcbeta.com/viewthread-1514621-1-1.html)
* [Garbage Collector](http://forum.ru-board.com/topic.cgi?forum=2&topic=5328)

# KEY Database

* [Blocked_Keys_VAMT.txt](https://github.com/CNMan/balala/blob/master/Blocked_Keys_VAMT.txt): valid keys, have been blocked(confirmed database by VAMT).

* [Blocked_Keys_PIDKEY.txt](https://github.com/CNMan/balala/blob/master/Blocked_Keys_PIDKEY.txt): valid keys, have been blocked(unconfirmed database from PIDKEY).

* [Fake_Keys.txt](https://github.com/CNMan/balala/blob/master/Fake_Keys.txt): valid keys, have same keyid.

* [Unsupported_Keys.txt](https://github.com/CNMan/balala/blob/master/Unsupported_Keys.txt): valid NT 5.x keys, unsupported by VAMT, you can check them with [The Ultimate PID Checker](http://janek2012.eu/download/pidgen.v1.2.0.606.rar).

* [Undefined_Keys.txt](https://github.com/CNMan/balala/blob/master/Undefined_Keys.txt): valid keys, unsupported by VAMT, you need recheck them after add new pkconfig to VAMT.

* [Invalid_Keys.txt](https://github.com/CNMan/balala/blob/master/Invalid_Keys.txt): invalid keys, unsupported by VAMT.

* 如果你使用MS-KEY Tool收集序列号，复制Blocked_Keys.txt、Fake_Keys.txt、Unsupported_Keys.txt、Undefined_Keys.txt、Invalid_Keys.txt中的KEY到/keys/OldKeys.txt，MS-KEY Tool会自动过滤这些序列号。

#[Pull requests](https://github.com/CNMan/balala/pulls)

* 提交前请排序、去重

# [VAMT 支持的产品pkconfig信息](https://github.com/CNMan/balala/blob/master/pkconfig.csv)

注：部分产品需要自行添加相应的`pkconfig.xrm-ms`以提供支持。

* [Windows 10 ADK](http://download.microsoft.com/download/C/8/4/C84E1024-8994-4D32-9893-FEB3CBA772D1/adk/adksetup.exe): `C:\Program Files (x86)\Windows Kits\10\Assessment and Deployment Kit\VAMT3\pkconfig\`
* [Windows 8.1 ADK](http://download.microsoft.com/download/6/A/E/6AEA92B0-A412-4622-983E-5B305D2EBE56/adk/adksetup.exe): `C:\Program Files (x86)\Windows Kits\8.1\Assessment and Deployment Kit\VAMT3\pkconfig\`

# 致谢

* [hnfeng@bbs.pcbeta.com](http://bbs.pcbeta.com/viewthread-1514621-1-1.html)

* [Ratiborus@forum.ru-board.com](http://forum.ru-board.com/topic.cgi?forum=2&topic=5328)

* [janek2012@forums.mydigitallife.info](http://forums.mydigitallife.info/threads/20816)

* [ASV93@forums.mydigitallife.info](http://forums.mydigitallife.info/threads/48346)
