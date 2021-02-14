# spamall
pkg update -y
pkg upgrade -y
pkg install python2 -y
pkg install git-y
git clone https://github.com/MR414N-ID/spamall
cd spamall
pip2 install mechanize -y
pip2 install requests -y
python2 spamall.py
