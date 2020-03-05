Simple GUI interface mockup to demonstrate Filesharing (based on dexp2p) Komodo technology.

Special thanks to https://github.com/theblackmallard for great UX theme

Dependencies:
```
python 3.7+ is needed (because of this bug https://stackoverflow.com/questions/52440314/ttk-spinbox-missing-in-tkinter-ttk/52440947)
sudo apt-get install python3-pip libgnutls28-dev python3-tk python3-pil python3-pil.imagetk
pip3 install setuptools wheel slick-bitcoinrpc ttkthemes
```


![screenshot](https://i.imgur.com/f3fE7Tb.png)

## To use:

### 1. Start FILET1 chain

At the moment it's just a test chain which hardcoded there https://github.com/tonymorony/P2PFileShare-Py/blob/master/main.py#L9 it might be non-actual already if I'll forgot to update this README

```
./komodod -ac_name=FILET1 -dexp2p=2 -ac_supply=999999 -addnode=95.217.44.58
```

### 2. Start program as `python3 main.py`
