# terminal-shortcuts
* Linux terminal-shortcuts

## Sysinfo
* uname -a
* inxi -Fxz

## pacman Tipps und Tricks
* pacman -S --search citrix
* pacman -Q -l | grep citrix

## ssh Tipps und Tricks
* scp username@from_host:file.txt /local/directory/
* scp -rv sshuser@192.168.178.109:/var/www/Adventskaleder/ andi@andis-yoga900:/home/andi/Software/www/
* ssh-keygen
* ssh-copy-id sshuser@192.168.178.109

## rfkill ist zum Blocken der Funkverbindungen beim Flugzeugmodus 
* rfkill list all
* sudo rfkill unblock bluetooth
* sudo rfkill unblock wlan

## sym Links setzen:
* ln -s /pfad/zur/Datei.txt /pfad/zur/Destination/

## reboot to BIOS
* systemctl reboot --firmware-setup

## speedtest device sda1 mit 1024MB Daten
* dd if=/dev/sda1 of=tempfile bs=1M count=1024 conv=fdatasync,notrunc

## Ordner Große mit Inhalt
* du -sbh /Ordner/der/untersucht/wird # leer = aktueller Ordner

## Dateien Suchen angeblich xD
* find 'Bilder/Andrea/' -print

## Nach der  Binärdatei, den Quelltexten und Handbuchseiten eines Befehls suchen
* whereis 

## Netzwerkumgebung 
* nmap -sn 192.168.178.0/24

## welche ports sind online
* sudo netcap
* sudo pacman -S netactview
