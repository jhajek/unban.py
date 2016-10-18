# unban.py
This a repo containing a python script to undo the banning caused by DENYHOSTS when you fail the requisite number of logins

You actually need to stop denyhosts, then remove the offending entry from 6 other files and restart it.
The affected files are:
* /var/lib/denyhosts/hosts
* /var/lib/denyhosts/hosts-restricted
* /var/lib/denyhosts/hosts-root
* /var/lib/denyhosts/hosts-valid
* /var/lib/denyhosts/users-hosts
* /etc/hosts.deny

http://serverfault.com/questions/189932/how-to-delete-ip-address-from-denyhosts