## Lancer Snort et lire les logs 

### Pour lancer snort sur le bridge :
```bash
sudo snort -c <snort.lua> -R <rules_path> -i <bridge> -A alert_fast
```
