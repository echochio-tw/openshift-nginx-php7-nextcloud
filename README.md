# OpenShift Nginx PHP 7 nextcloud 12.0.0 Cartridge
Nginx 1.9 with PHP 7.0 owncloud  on OpenShift.

* Nginx: 1.11.6
* PHP: 7.0.13
* Composer: 1.2.4
* owncloud: 10.0.2

## Installation

### Web Console
<a href="https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/pinodex/openshift-cartridge-nginx-php7&amp;name=php"><img alt="Run+PHP+7+on+OpenShift" src="https://launch-shifter.rhcloud.com/launch/light/Run%20PHP%207%20on.svg" /></a>

Alternatively, you can use this [cartridge definition](http://cartreflect-claytondev.rhcloud.com/github/pinodex/openshift-cartridge-nginx-php7) on application creation page.


### Base : 
```
https://github.com/pinodex/openshift-cartridge-nginx-php7
```

### Create 
```
# rhc app create nextcloud mysql-5.5 cron http://cartreflect-claytondev.rhcloud.com/github/echochio-tw/openshift-nginx-php7-nextcloud
```
### login info
```
username : admin
Password : admin

```

### web http://nextcloud-XXXXX.rhcloud.com login

![alt tag](https://github.com/echochio-tw/openshift-nginx-php7-nextcloud/raw/master/pic/login.png)

