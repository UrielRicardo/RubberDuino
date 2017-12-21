# RubberDuino
apt-get update -y
cd /ArduinoIDE
chmod +x install.sh
./install.sh
----------------------

apt-get install libusb-1.0-0 libusb-1.0-0-dev autoconf -y
git clone https://github.com/dfu-programmer/dfu-programmer
cd dfu-programmer/
./bootstrap.sh
./configure
make
make install
----------------------------------------------------------

cd ~/RubberDuino/ArduinoUNO_HID/
./script.sh

-----------------------------------------------------------
