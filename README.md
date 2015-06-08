# failover
2 uplnk failover

add job to /etc/crontab

```bash
echo "* *  * * * root /etc/network/failover.sh" >> /etc/crontab
```

