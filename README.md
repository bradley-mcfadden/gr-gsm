The gr-gsm project
==================
The project contains gnuradio blocks and tools for receiving GSM transmissions.

Installation
------------

On clean Ubuntu 14.04 following packages are required in order to compile gr-gsm:
```
sudo apt-get install gnuradio gnuradio-dev uhd-host gr-osmosdr        #use this command if you don't want to compile gnuradio sources
sudo apt-get install git cmake libboost1.55-all-dev libcppunit-dev swig doxygen liblog4cpp5-dev
```

Download gr-gsm sources with following command:

```
git clone git@github.com:Jakotako/gr-gsm.git
```

and compile it:

```
cd gr-gsm
mkdir build
cmake ..
make
sudo make install
```
