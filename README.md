# cuckoo-workshop-2018

Project site:
https://cuckoosandbox.org

Docs:
https://cuckoo.sh/docs/

Develompent install:
https://cuckoo.sh/docs/development/package.html

Requirements:
https://cuckoo.sh/docs/installation/host/index.html

Repo:
https://github.com/cuckoosandbox

VMVare unlocker:
https://github.com/DrDonk/unlocker

```
sudo -H pip install -U pip setuptools
sudo -H pip install virtualenv
brew install libmagic cairo pango openssl
mkdir ~/virtualenv
virtualenv ~/virtualenv/cuckoo-development
. ~/virtualenv/cuckoo-development/bin/activate
mkdir workshop
cd workshop
git clone https://github.com/cuckoosandbox/cuckoo
cd cuckoo/
python stuff/monitor.py
python setup.py sdist develop
cuckoo
rm -rf ~/.cuckoo/
```


