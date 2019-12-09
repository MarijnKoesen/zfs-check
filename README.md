Simple script to check your ZFS pools and sends out emails in case of an error.

It checks for the health, disk space, scrub time etc.

Install in cron:

```
7 * * * *  /usr/local/bin/zfs-check
```
