## Lancer Snort et lire les logs 

### Pour lancer snort sur le bridge :
```bash
sudo snort -i br-949d53056adf -c /etc/snort/snort.conf -l /var/log/snort
```

### Pour lire les logs :

```bash
tail -f /var/log/snort/fast.log
```
