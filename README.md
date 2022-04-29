
FusionPBX Install
--------------------------------------
A quick install guide & scripts for installing FusionPBX in a docker environment.

## Operating Systems
### Debian
Debian 9 is the preferred operating system by the FreeSWITCH developers. It supports the latest video dependencies and should be used if you want to do video mixing. Download Debian 9 Stretch at https://cdimage.debian.org/cdimage/release/current/

```sh
wget -O - https://raw.githubusercontent.com/samsonkehinde/fusionpbx-install.sh/docker/pre-install.sh | sh;
cd /usr/src/fusionpbx-install.sh && ./install.sh
```

## Security Considerations
Fail2ban is installed and pre-configured for all operating systems this repository works on besides Windows, but the default settings may not be ideal depending on your needs. Please take a look at the jail file (/etc/fail2ban/jail.local on Debian/Devuan) to configure it to suit your application and security model!

## ISSUES
If you find a bug sign up for an account on www.fusionpbx.com to report the issue.
