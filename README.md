# linux-shenanigans
Useful Linux commands that I came across

**Cron job on file creation**

package used - _incron_

sudo apt-get install incron

**Automount external drive**

UUID=<uuid> <pathtomount> ntfs uid=<userid>,gid=<groupid>,umask=0022,sync,auto,rw 0 0

find disk uuid by - sudo blkid

find uid and gid by - id
