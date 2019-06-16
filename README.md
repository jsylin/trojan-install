# trojan-install
trojan install on my vps
1.build install  
Install these dependencies before you build (note that the test has some additional dependencies):

CMake >= 3.7.2
Boost >= 1.66.0
OpenSSL >= 1.0.2
libmysqlclient
For Debian users, run sudo apt -y install build-essential cmake libboost-system-dev libboost-program-options-dev libssl-dev default-libmysqlclient-dev to install all the necessary dependencies.

Clone
Type in

git clone https://github.com/trojan-gfw/trojan.git
cd trojan/
to clone the project and go into the directory.

Build and Install
Type in

mkdir build
cd build/
cmake ..
make
ctest
sudo make install  
####if stest is fail,just input next step "make install"  
or just find binary file of trojan in build after making. and "./binary of trojan" is ok.
