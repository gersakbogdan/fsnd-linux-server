## Udacity FSND -  P5 Linux Server Configuration
Udacity Full Stack Web Developer Nanodegree P5 Linux Server Configuration Project

### SSH
IP: 52.33.89.130
PORT: 2200

### Recipes catalog project (Apache, Python, Flask, SQLAlchemy, WSGI)
http://ec2-52-33-89-130.us-west-2.compute.amazonaws.com/

### Packages
In order to complete the requirements the following packages were installed:
  * PostgreSQL
  * Apache2
  * Python
  * Flask, SQLAlchemy, Flask-Login, Flask-WTF, RAuth, Pillow, XMLDict, mod_wsgi
  * Virtualenv
  * PHP5
  * GIT
  * unattended-upgrades
  * Fail2Ban
  * Glances, Nagios
  * ntp

### Automatic Updates
 * For package updates 'unattended-upgrades' package is used and it was configured to check for updates daily

### Security Improvements
 * To improve server security and to stop systematic login attempts by users or bots **fail2ban** package was installed and configure. fail2ban is creating rules that can automatically alter the iptables firewall configuration based on a predefined number of unsuccessful login attempts.
 
 
### System monitor
  * Nagios web interface: http://52.33.89.130/nagios/

### Resources
  * [PostgreSQL](http://www.cyberciti.biz/faq/howto-add-postgresql-user-account/)
  * [Automatic Updates](https://help.ubuntu.com/lts/serverguide/automatic-updates.html)
  * [Fail2Ban](https://www.digitalocean.com/community/tutorials/how-to-protect-ssh-with-fail2ban-on-ubuntu-14-04)
  * [LAMP](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-14-04)
  * [Nagios](https://www.digitalocean.com/community/tutorials/how-to-install-nagios-4-and-monitor-your-servers-on-ubuntu-14-04)
  * [Tyme Synchornisation](https://help.ubuntu.com/lts/serverguide/NTP.html)
