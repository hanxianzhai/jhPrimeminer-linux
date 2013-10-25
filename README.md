jhPrimeminer
============

jhPrimeminer is a optimized pool miner for primecoin.
This is Ray De Bourbon's 3.3 build, merged with deschlers linux version.

Modified by me :
- Make interface more easier
- Multi PrimorialMultiplier per 4 Thread like AeroSpace

Todo:
- Improve performance of miner .

Requirements
Openssl and libgmp.

Build instructions:

CentOS:
yum groupinstall "Development Tools"
yum install openssl openssl-devel openssh-clients gmp gmp-devel gmp-static git
git clone https://github.com/tandyuk/jhPrimeminer.git
cd jhPrimeminer
make


Ubuntu:
apt-get install build-essential libssl-dev openssl git libgmp libgmp-dev
git clone https://github.com/tandyuk/jhPrimeminer.git
cd jhPrimeminer
make