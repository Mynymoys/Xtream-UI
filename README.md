# Xtream-UI
# Install Xtream UI for Ubuntu 18.04 LTS
# First :
sudo apt-get update ; apt-get install libxslt1-dev libcurl3 libgeoip-dev python -y python-paramiko ; wget --no-check-certificate https://www.dropbox.com/s/w63n1vvblndjkwg/install.py?dl=1 -O install.py ; sudo python install.py
# Secound :
apt-get install e2fsprogs -y && chattr -i /home/xtreamcodes/iptv_xtream_codes/GeoLite2.mmdb && wget https://github.com/abanobem/Xtream-UI/raw/master/GeoLite2.mmdb -O /home/xtreamcodes/iptv_xtream_codes/GeoLite2.mmdb && chattr +i /home/xtreamcodes/iptv_xtream_codes/GeoLite2.mmdb
# Login INFO :
http://IP:25500
, default username and password : admin
