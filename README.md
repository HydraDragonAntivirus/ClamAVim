# Hydra Dragon Anti-virus For Linux

<p align="center">
<img src="assets/logo.png" width= 200px>
</p>

## Notice
You need use Firefox as your browser
## Feautres

- Real-time protection
- Web protection
- SHA256-SHA1-MD5-SSDEEP-TLSH calculator
- Big databases for free. Above the 65 million virus hashes here
- ClamAV on Python
- Rootkit scanner are united in one python script
## Download

Download full version [here](https://mega.nz/folder/n85EkQwa#6E6xSXO5Y2NQ4rzrg-nIzA)
- Phising Database: https://github.com/mitchellkrogza/Phishing.Database
### Read before using
- Don't forget give permission access.
- It really disconnect infected ip address and it deletes file so be careful!
- Don't forget to use clamonacc
- Test the suspicous file in home folder
## Contact
<a href="https://discord.gg/W2N27aF5"><img src="https://img.shields.io/discord/72895893221067986?style=flat-square&logo=appveyor"></a>
### semaemirhan555@gmail.com
## License
Public Domain License ![image](https://github.com/HydraDragonAntivirus/Hydra-Dragon-Antivirus-Linux/assets/142328963/c2679d99-7255-404b-aa5a-0e123d793645)
## How To Give Root Access To Program
sudo python Antivirus.py
## Current Statics
I have **65167844+** normal virus hashes **1618883+** virus or illegal websites and IP address list  **2.5 million** virus or safe website. Total fuzzy hashes
**4882073**+ Phising **1042529** and **4.000.00+** secureinfo.com signatures.
## Detection Rate
ClamAV 60% Hydra Dragon Antivirus 65%
## Collected Datas
No data collected
## Installation On Arch Linux For Beginners
### Please First Test It On Virtual Machine Antivirus Might Be Crash Your System
### Tested On Cachy OS And If You Looking For Debian Tested On Kali Linux And It Worked But Best Works At Debian Based Distros For All Features
- sudo pacman -Sy
- sudo pacman -S python
- sudo pacman -S python-appdirs
- sudo pacman -S python-tlsh
- sudo pacman -S strace
- sudo pacman -S python-pyinotify
- sudo pacman -S rkhunter
- sudo pacman -S clamav
- sudo pacman -S firejail
### Download This Files
- http://database.clamav.net/main.cvd
- http://database.clamav.net/daily.cvd
- If you got banned try again in 24 hours
- Save at Downloads
- cd
- cd Downloads
- git clone https://aur.archlinux.org/chkrootkit.git
- cd chkrootkit/
- makepkg -si
- Then check installation by typing sudo chkrootkit
- cd ..
- sudo cp main.cvd /var/lib/clamav/
- sudo cp daily.cvd /var/lib/clamav/
- Type sudo clamscan to check clamscan
- Installing ssdeep:
- git clone https://github.com/DinoTools/python-ssdeep.git
- cd python-ssdeep/
- sudo pacman -S python-setuptools
- sudo pacman -S python-pip
- sudo pacman -S ssdeep
- python setup.py build
- sudo python setup.py install
- cd ..
  sudo nano /etc/clamav/freshclam.conf
  Then paste this:
  DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfo.hdb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfo.ign2
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/javascript.ndb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/spam_marketing.ndb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfohtml.hdb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfoascii.hdb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfoandroid.hdb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfoold.hdb
DatabaseCustomURL https://www.securiteinfo.com/get/signatures/9e46fcf748515c2e273120875878728d48c4aa222679a44eb5bbddbcd59914f4dc15ae118bd3e47a0b1e6129009ee1f31860406710c2581773be718f70f515ae/securiteinfopdf.hdb
Then Ctrl+S then Ctrl+E then sudo freshclam
### Download Antivirus from mega.nz link: https://mega.nz/folder/n85EkQwa#6E6xSXO5Y2NQ4rzrg-nIzA
- Save At Downloads
- unzip Antivirus.zip
- cd Antivirus\
- Type sudo python Antivirus.py you are done
- You can also start without root by typing python Antivirus.py
- If you have a problem create issue topic or try reboot
## How To Update Databases Manually?
https://www.youtube.com/@hydradragonantivirus Watch my videos here. It will help you.
