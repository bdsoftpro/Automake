autoreconf --install
mkdir build
cd build
../configure
make
sudo make install
autoconf_hello_world
sudo make uninstall
