# Installation Instructions

This is a frozen build of `liblognorm` to deal with CEF files from an ArcSight instance. Some modifications to the source code have been made to correctly parse the CEF data we had. In order to use the updated code the binaries need to be built from source.

## Install for Ubuntu Systems

### Pre-reqs
```
sudo apt-get install -y make libtool pkg-config autoconf automake
```

### Build/Install
```
autoreconf -vfi
./configure
make
sudo make install
```

### Post-install
```
sudo ldconfig
```

## Install for other systems

Should be similar to the Ubuntu steps but has not been tested on other systems.
