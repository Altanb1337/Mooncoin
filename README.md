
Mooncoin 1.875.1 compiled from Mooncoin 1.871.1.0 minkiz.co
https://github.com/mooncoin-project/mooncoin-landann
(1) an original logo from https://github.com/mooncoin-project/mooncoin


### How to build Mooncoin

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC 44663
P2P 44664
