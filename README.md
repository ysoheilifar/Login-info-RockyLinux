# Login information Script on Rocky Linux

1. Copy `login-info.sh` file in `/etc/profile.d`

2. Set `755` or `777` permission to `login-info.sh`
```bash script
cd /etc/profile.d
cdmod 755 login-info.sh

```
3. Logout and login again then enjoy the information