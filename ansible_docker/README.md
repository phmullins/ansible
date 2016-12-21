## About
An Ansible play that installs Nginx and PHP 7 using <a href="http://www.dotdeb.org">www.dotdeb.org</a>. Dotdeb is an extra repository providing up-to-date packages for Debian servers. In particular, Nginx, PHP 7.0, 5.6, 5.5 and 5.4 (obsolete), useful PHP extensions : apcu, imagick, mongo, Pinba, xcache, Xdebug, XHprof, MySQL 5.6, Redis, and Zabbix.

## Usage
The only thing that needs to be changed before running the play is the `hosts` file. Open it and change the IP address and username to match what you have. After that, run the following from the command-line:

```
$ ansible-playbook -i hosts nginx_php.yml --ask-become-pass
```

Once finished, open the IP in a web browser and test to make sure Nginx and PHP are running properly.

## Author
Created by [Patrick H. Mullins](http://www.pmullins.net). You can find me on  [Twitter](https://twitter.com/phmullins) and on [Telegram](https://telegram.org/) as @pmullins.

## License
Source is released under the FreeBSD (BSD-2-Clause) License [license](license.md).
