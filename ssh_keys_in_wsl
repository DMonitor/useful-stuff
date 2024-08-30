# SSH Keys In WSL

Create and empty `~/.ssh` folder and edit `/etc/fstab` with the following entry

```
C:\Users\[WINDOWS USERNAME]\.ssh\ /home/[Linux USERNAME]/.ssh drvfs auto,rw,noatime,uid=1000,gid=1000,case=off,umask=0077,fmask=0177 0 0
```

The keys will be shared between folders with no complaining about key permissions
