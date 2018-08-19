# MMDVM_activity
Publish repeater activity on a public webserver, independent of the network (BM, or what else), by exploiting MMDVM logs.


## Requires
+ php on repeater
+ curl on repeater
+ php on public webserver
+ MySQL on public webserver

### Installation On repeater  with :
```
apt-get update
apt-get install curl libcurl3 php5-curl
apt-get install php5-cli
```

## Thanks
The MMDVM log treatment is MW0MWZ functions script included in the famous [pi-star](http://www.pistar.uk/).
