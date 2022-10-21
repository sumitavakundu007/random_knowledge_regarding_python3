# Random knowledge regarding python3

## Some random informations of packages installed via yum or pip3
## Package location installed via 'setup.py' file
```bash
cd .local/lib/python3.X/site-packages/
```

## Suppose you have installed Python3.X in a custom path and you want to use pip3.X, then.....
# You have to install pip3.X first if it is not installed
# If you are behind proxy, then first set proxy of wget and pip
Set proxy for pip3.X
```bash
export https_proxy=http://username:password@proxy_server:port
export http_proxy=http://username:password@proxy_server:port
```
Install pip3.X for Python3.X
```bash
wget https://bootstrap.pypa.io/get-pip.py
python3.8 get-pip.py
```
