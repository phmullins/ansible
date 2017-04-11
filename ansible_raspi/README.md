## About
An Ansible play that updates your Raspberry Pi, installs Bash aliases, configures Git, and optimizes the Raspbian OS to run as quickly as possible. In particular, check out the changes made in `/boot/config.txt`.

## Usage
The only thing that needs to be changed before running the play is the `hosts` file. Open it and change the IP address and username to match what you have. After that, run the following from the command-line:

```
$ ansible-playbook an_raspi_configure.yml -i hosts.txt
```

## Author
Created by [Patrick H. Mullins](http://www.pmullins.net). You can find me on  [Twitter](https://twitter.com/phmullins) and on [Telegram](https://telegram.org/) as @pmullins.

## License
Source is released under the FreeBSD (BSD-2-Clause) License [license](license.md).
