
## Lancer Suricata et lire les logs

### Pour lancer suricata sur le bridge :
```bash
sudo suricata -i br-949d53056adf -v
```
ou
```bash
sudo systemctl restart suricata
```

### Pour lire les logs :
```bash
tail -f /var/log/suricata/fast.log
```
