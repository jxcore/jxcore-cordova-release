### JXcore Cordova Binary Repository

In order to install one of the binaries follow the steps below;

##### 1- Download JXcore from [jxcore.com/downloads](http://jxcore.com/downloads)

##### 2- [Optional] In case you don't have `wget` or something similar is installed

for unix;
```
sudo jx install -g download-cli

```

for windows
```
jx install -g download-cli
```

##### 3- Download `jxcore-cordova` binary into your Cordova/Phonegap project
 
```
download http://jxcordova.cloudapp.net/0.0.8/io.jxcore.node.jx
jx io.jxcore.node.jx
```

Please note, that the url specifies an exact version of jxcore-cordova.
For list of other possible versions see http://jxcordova.cloudapp.net.

##### 4- Install plugin
```
cordova plugins add io.jxcore.node/
```
 
 
#### Contributions
Please visit [jxcore-cordova](https://github.com/jxcore/jxcore-cordova/) for source codes 
and contribution.
