# easy-wi-install
easy-wi_install.sh allows a guided installation at Debian 8.0 and Ubuntu 14.04 systems. Supported are "Standalone Panel at a blank system", " Web Master", "Game Master" and "Voice Master". Other versions of those distributions might work but are untestet.
<br>
One line command
----------------
#### Run the following one liner as root
```
yum install -y wget;wget --no-check-certificate https://raw.githubusercontent.com/janovas/easy-wi-install/master/easy-wi_install.sh -O easy-wi_install.sh;chmod 755 easy-wi_install.sh;./easy-wi_install.sh 2>&1|tee easy-wi_install.log
```
