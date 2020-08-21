# conso_veolia
Based on Flobul/conso_veolia

Recupere la consomation d'eau de la veille sur le site Veolia IDF.
En cas de soucis, le script remonte une exeption.

## Installation pour un RPI 3B+

1. Tout d'abord isntaller python 3.7: https://installvirtual.com/install-python-3-7-on-raspberry-pi/
2. sudo apt-get install python3.7 xvfb iceweasel
3. sudo pip3.7 install selenium pyvirtualdisplay urllib3
4. wget https://github.com/mozilla/geckodriver/releases/download/v0.17.0/geckodriver-v0.17.0-arm7hf.tar.gz && tar xzfz geckodriver-v0.17.0-arm7hf.tar.gz && sudo mv geckodriver /usr/local/bin && rm geckodriver-v0.17.0-arm7hf.tar.gz
5. chmod +x /usr/local/bin/geckodriver
6. git clone -b master https://github.com/JohanSweck/conso_veolia.git
