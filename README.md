# ctftime-backup-loader

<b>ctfd-backup.py</b><br>
This python script makes auto-saving of CTFd Backup to the specified directory.<br>

<b>script.sh</b>
This bash command to execute ctf-backup.py.

## Installing:
```bash
pip install BeautifulSoup4
pip install requests
pip install wget
```


Write in <b>crontab</b> (crontab -e) to save ctf-backup.zip every 15 min:
```bash
*/15 * * * * /home/kali/script.sh
```

## Running:
```bash
crontab
```
