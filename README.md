Filter Content
==============


## Install

See [this](https://www.howtoforge.com/dansguardian-content-filtering-with-transparent-proxy-on-ubuntu-9.10-karmic) tutorial.


After configuring lists:

```
dansguardian -r
```



## Banned List

Ban all sites.

/etc/dansguardian/bannedsitelist file

```
#Blanket Block.  To block all sites except those in the
#exceptionsitelist file remove the # from the next line to leave
#only a '**':
**
```


## Exception List

Permited list.

 /etc/dansguardian/exceptionsitelist

```
hidabroot.org
```



## Resources

* https://wiki.archlinux.org/index.php/DansGuardian#Blacklists
* https://www.techrepublic.com/blog/smb-technologist/block-social-networking-sites-with-dansguardian/
* https://help.ubuntu.com/community/ParentalControls
* https://www.techrepublic.com/blog/diy-it-guy/diy-filter-content-for-free-with-dansguardian/
* http://e2guardian.org/cms/index.php/download
* https://www.linuxuprising.com/2019/11/timekpr-next-is-linux-parental-control.html
