# iocage-plugins
Official PersonalNAS iocage plugins for [FreeNAS](http://www.freenas.org), and [FreeBSD](http://www.freebsd.org)

Plugin Json files are added to this repo, along with a respective icon in icons/

When a plugin is made 'official' it should be added to the INDEX json and
it will appear in iocage's plugin listing

# Installing Plugins

## Using Local File
```
iocage fetch -P /the/path/to/transmission.json ip4_addr="dwc0|192.168.0.110" -n transmission 
```

## Pulling from Internet
```
iocage fetch --plugins --name "transmission" ip4_addr="dwc0|192.168.0.110"
```

