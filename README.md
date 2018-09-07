# centos-cron-reboot-system

This script will only works for Linux distros with Yum package managemente
Was only tested with Centos 7

Copy the script to the path:
`
/usr/local/sbin
`

set a cronjob with the following command:

`
* 03 * * 0 /usr/bin/python /usr/local/sbin/reboot-server.py > /dev/null 2>&1
`
