# unriad
rclone fix
I had this issue too when I first installed.

Was able to solve it by creating the .rclone.conf file manuallly using

```
touch /boot/config/plugins/rclone/.rclone.conf
```

then re-install rclone from Apps.

