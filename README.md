# rpi-phantomjs
PhantomJS compiled for the Raspberry Pi (compiled on a Raspberry Pi 3, AMRv7, on Jessie).
Current version: 2.1.1

Steps to compile:
```bash
sudo apt-get install build-essential g++ flex bison gperf git ruby perl python \
  libsqlite3-dev libfontconfig1-dev libicu-dev libfreetype6 libssl-dev \
  libpng-dev libjpeg-dev python libx11-dev libxext-dev
git clone git://github.com/ariya/phantomjs.git
cd phantomjs
git checkout 2.1.1
git submodule init
git submodule update
python build.py
```

